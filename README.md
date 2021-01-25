# WPfaka
基于WordPress的自动发卡解决方案 功能丰富、安全、高度自由、美观

# wordpress发卡手册
## 为什么每个发卡站长都需要wordpress发卡站
现在那些发卡网站，只是说是发卡程序，不能算发卡网站，看到好几个站长使用说明要单独写一个文档发给顾客，效率不高
wordpress是一个商城系统，更全面
## 介绍
wordpress发卡，是用wordpress作为平台，用woocommerce作为商城系统，woocommerce license manger作为发卡程序的一套发卡系统。依托wordpress平台，wordpress发卡可以实现高度自由，安全性，美观
## 插件列表
woocommerce
license manager
alipay

 Checkout Field Editor for WooCommerce+buy now
 wordfense
 wp-admin change
 
 All-in-One WP Migration+All-in-One WP Migration File Extension
starter templates+astra+elementor

Google Analytics for WordPress by MonsterInsights
WP Mail SMTP
多合一SEO集

看起来麻烦，但是wordpress逻辑清楚，安装之后运行顺畅，更新也很方便
安全性高，数据可追踪、插件丰富、可扩展性强
更正式

避免麻烦，提供几个"一键安装"包，用all in one migration一键恢复即可，放在百度云，需要的自取
第一件事：添加用户、删除用户

## 安装步骤
1. 安装宝塔环境
可以参考这里 [github 宝塔](https://github.com/aaPanel/BaoTa)
Centos
yum install -y wget && wget -O install.sh http://download.bt.cn/install/install_6.0.sh && sh install.sh
Ubuntu/Debian
wget -O install.sh http://download.bt.cn/install/install-ubuntu_6.0.sh && sudo bash install.sh
2. 安装wordpress
宝塔面板——软件商店——一键部署——___WordPress——一键部署___
3. 开启https
宝塔面板——网站——设置——SSL——let's Encrypt——申请——强制https
3. 安装插件 Starter Templates 
    Elementor——选择模板——导入
4. 安装其他插件 

## 网站设置
1. 管理员账号、密码
wordpress工具栏——设置——固定连接——Change wp-admin login
2. 用户注册、登录
用户——添加管理员账户
用户——删除默认账户（如果用的一键包）
2. 网站标题、logo
网站——工具栏——自定义——页眉——网站标识——标志（网页左上角logo）/站点图标（标签页小logo）
2. 页头、页脚
页脚——footer
2. 网页内容
可视化编辑器Elementor

## 插件设置
1. change wp admin
2. woocommerce
3. license
    添加产品
    单一产品
    可变产品
    添加卡密、库存、自动发卡
4. 支付宝
    开通当面付、对接、付款提示
5. checkoutfield
6. buy now
7. wordfense
8. WP Mail SMTP
9. All-in-One WP Migration
    网站备份和恢复

