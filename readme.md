# zshrc
一键式配置zsh(自用)
在知乎大神的基础上进行修改,配置自己的.zshrc

我的repo地址 https://github.com/yiny0liuyin/zshconfig.zshrc

效果
image!
image!

实现的功能
自动跳转
高亮
安装皮肤powerlevel9k
命令提示
自动补全
….

依赖
请检查是否已经安装git,zsh,oh-my-zsh.
大陆用户确保已经使用了代理

请使用127.0.0.1:1086的socks端口 否则请自行修改 安装.zshrc 中的 export all_proxy=127.0.0.1:1086 改成 其他
请使用 powerline字体
安装oh-my-zsh
请确保已安装curl

sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
1
安装antigen
cd ~ && git clone https://github.com/yiny0liuyin/zshconfig.zshrc.git && cd zshconfig.zshrc && mv 安装antigen.zshrc ~/.zshrc && zsh
1
使用
安装完成后 请执行

cd && cd zshconfig.zshrc && mv .zshrc ~/.zshrc 
1
如果你觉得麻烦请执行(忽略以上两条代码)
git clone https://github.com/yiny0liuyin/zshconfig.zshrc.git && cd zshconfig.zshrc && mv 原始.zshrc ~/.zshrc &


Demo: 

![](https://cdn.jsdelivr.net/gh/innei/img-bed@master/20200115195551.png)

### 使用方法 

clone 此仓库，将其中一个 `.zhsrc` 改名并放入 `~`



### 周边

`theme` 文件夹下提供了终端的配色

`font`文件夹下提供了我使用的等宽字体。其中` Operator Mono` 字体提供了原版，连字版以及图片扩展补丁版。效果如下图：

`Operator Mono SSm Lig Book Nerd Font Plus Font Awesome Plus Font Awesome Extension Plus Octicons Plus Power Symbols Plus Font Logos (Font Linux) Plus Material Design Icons`



![](https://cdn.jsdelivr.net/gh/innei/img-bed@master/20200115200014.png)

![](https://cdn.jsdelivr.net/gh/innei/img-bed@master/20200115200208.png)

![](https://cdn.jsdelivr.net/gh/innei/img-bed@master/20200115200247.png)
