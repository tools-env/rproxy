### 构建rproxy命令

如果要编译带界面的客户端需要加上 -tags gui 如下面的   
go build -i -ldflags="-H windowsgui" -tags gui -o rproxy_GUI.exe   

最后面下面下载对应的govcl二进制：  
https://github.com/ying32/govcl/releases/download/v1.2.2/Librarys-1.2.2.zip