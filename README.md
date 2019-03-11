# Online Markdown Converter

微信公众号编辑器有一个十分头疼的问题——粘贴出来的代码，格式错乱，而且特别丑。本项目是一个微信公众号 
Markdown 编辑器，它能够解决这个问题。

## 开发说明

1. 安装NodeJS
2. 执行`npm install webpack -g` 
3. 在项目根目录执行`npm install`
4. 修改src中的代码，只需在项目根目录执行`webpack --watch` ，即可构建并生成新代码到`docs`目录。


## 使用说明

1. 准备一个静态网页服务器，例如NGINX、Apache、Lighttpd、Tomcat...Whatever!
2. 将docs目录中的内容拷贝奥你的静态网页服务器中。
3. 访问吧！

## 鸣谢

* 小胡子哥（插件原作者）：<https://github.com/barretlee>

### LICENSE

MIT
