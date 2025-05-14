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

# 3. 启动 Clash

./clash -d .

💡 若提示权限不足，请先执行：

chmod +x clash

