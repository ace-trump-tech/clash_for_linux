###一、安装包下载
        首先点击这个下载链接，进入安装包下载界面。或者你是无图形化界面，也可以用这个指令。

git clone https://github.com/ace-trump-tech/clash_for_linux.git
>>>下载链接<<<


        先点击这个Star，然后点击code，接着Download ZIP。


###二、神奇小软件安装
        下载下来的文件一共有两个，一个是clashpremium-nightly-linux-amd64.tar.gz，这个就是安装包，将其解压，如果你是纯界面模式的话，解压指令如下。

tar -zxvf clashpremium-nightly-linux-amd64.tar.gz
  其中，-z 表示处理 gzip 压缩，-x 表示解压，-v 是显示解压过程中的文件信息（可选，如果不加 -v，解压过程不会显示文件列表），-f 用于指定文件名。解压完了之后会有一个叫做clash的文件夹，然后把iKuuu_V2.yaml放在clash这个文件夹里面。


        执行 ./clash -d . 即可启动 Clash，同时启动 HTTP 代理和 Socks5 代理。如提示权限不足，请执行 

chmod +x clash
###三、端口设置
        Host: 127.0.0.1，端口: 9090。以 Ubuntu 19.04 为例，打开系统设置，选择网络，点击网络代理右边的 ⚙ 按钮，选择手动，填写 HTTP 和 HTTPS 代理为 127.0.0.1:7890，填写 Socks 主机为 127.0.0.1:7891，即可启用系统代理。
        如果你没有图形界面，使用以下代码也行：

export http_proxy="http://127.0.0.1:7890"
export https_proxy="http://127.0.0.1:7890"
export socks_proxy="socks5://127.0.0.1:7891"
###四、梯子测试
        自己访问google网站或者其他的神奇小网站即可。
