# readme

## install

- osx: 請參考 wiki

## 模組的使用

**關於模組的使用測試，可參考 wiki**

## about client app : 因應不同環境，使用的不同

- osx client : 請參考 wiki

## cmd : ejabberdctl 測試心得

> 因 官方文件有點不清楚，故特增加此

- ex : check user resource
    - 指令 `ejabberdctl user_resources [user_name] [vhost]`
	   - `user_name` : 非 name@{vhost}，只是單純的 name， ex : 1728@{vhost}，取出 `1728`
	   - `vhost` : 為 vhost 的全名，請參考 admin-console 中的 vhost 部分

## nodejs plugins

> 參考 nodejs-plugins/
> 主要為獲取某些參數

- feature : 自定義 auth 參數，自定義 cmd 參數
