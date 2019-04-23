# ss-panel-v3-mod_Uim 一键搭建脚本

wget -N --no-check-certificate https://raw.githubusercontent.com/marisn2017/ss-panel-v3-mod_Uim/master/script.sh && chmod +x script.sh && ./script.sh

使用方法与魔改版一样~

请根据提示完成搭建

如果遇到搭建lnmp完成后卡顿，如下图

lnmp卡顿
请手动点Ctrl + C 再继续搭建【只需要按一次，同时按压】

默认账号：marisn@67cc.cn

默认密码：marisn

搭建完后请务必在前端后台更改账号密码

完成前端搭建请在网站内新建节点

!!!注意进入前端后，第一件事就是先新建节点

管理面板–>节点列表–>右下角加号–>输入信息

唯一有点不一样的是 后台新建节点时，需注意节点名称的格式为

香港 普通节点1 - 100M带宽
美国 VIP节点1 - 10G带宽

前缀为/home/wwwroot/default/public/images/prefix里的图片名称 需自己对应

再次运行上面的脚本

选择添加节点，根据脚本提示操作

mukey值请在配置文件中更改，默认可不更改

配置文件路径：

/home/wwwroot/default/config/.config.php
因为文件被隐藏，所以用SFTP下载下来修改，推荐使用notepad++修改

所有要自定义的东西请在配置文件中更改

其他问题
以后新建ss-panel节点的时候，遵循先第二步后第三步的顺序，切勿没有节点即新建node,否则可能因为读取不到id信息而报错。

数据库采用端口888访问，如http://ip:888/ 默认账号密码root

如果你想自定义端口，可以在后台管理中心修改用户端口，从而达到自定义端口。
第一次使用请把1025端口重置才会有网哦~
管理面板–>节点列表–>编辑用户资料–>修改连接端口，保存
PS：如果相关端口已经被占用，则保存时会提示空白，请选择未开端口自定义

已经在 阿里云, 腾讯云，华为云，京东云，vultr，快云服务器上通过测试

支付系统对接教程：https://github.com/NimaQu/ss-panel-v3-mod_Uim/wiki/支付系统对接教程

魔改常用审计规则：https://github.com/NimaQu/ss-panel-v3-mod_Uim/wiki/魔改常用审计规则

其他支付方法请访问wiki：https://github.com/NimaQu/ss-panel-v3-mod_Uim/wiki/
