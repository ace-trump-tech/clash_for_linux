# Clash for Linux 安装指南

## 一、安装包下载

您可以选择以下任一方式进行下载：

- **图形化界面下载**：点击[GitHub - ace-trump-tech/clash_for_linux](https://github.com/ace-trump-tech/clash_for_linux)，点击 "Star" 后选择 "Code"，然后点击 "Download ZIP" 进行下载。

- **命令行下载**：在终端输入以下命令：
  ```bash
  git clone https://github.com/ace-trump-tech/clash_for_linux.git
## 二、神奇小软件安装
### 1. 解压安装包

   tar -zxvf clashpremium-nightly-linux-amd64.tar.gz

   
  参数说明：

-z: 处理 gzip 压缩

-x: 解压操作

-v: 显示解压过程（可选）

-f: 指定文件名

### 2. 配置文件放置
将 iKuuu_V2.yaml 配置文件移动至解压后的 clash 文件夹内

### 3. 启动 Clash

./clash -d .

💡 若提示权限不足，请先执行：

chmod +x clash

## 三、端口设置
图形化界面设置
以 Ubuntu 19.04 为例：

打开 "系统设置"

选择 "网络"

点击网络代理右侧的齿轮图标

选择 "手动" 模式

填写代理信息：

HTTP 代理：127.0.0.1:7890

HTTPS 代理：127.0.0.1:7890

Socks 主机：127.0.0.1:7891

终端设置

如果您没有图形化界面，可以使用以下命令设置代理：


export http_proxy="http://127.0.0.1:7890"

export https_proxy="http://127.0.0.1:7890"

export socks_proxy="socks5://127.0.0.1:7891"

##  四、梯子测试
完成上述设置后，您可以通过访问 Google 或其他网站来测试代理是否正常工作。

