# JavaScript编程一天入门

## 前言

每一讲建议时间30分钟左右. 如果卡住(比如超过一小时), 请在代码库开issue. 目的是让总时间控制在8小时左右, 让"一天入门"更符合实际.

## 目录

## 一 开编

从一句废话开始吧, 没有JavaScript, 就没有今天的网络花花世界. 它的前世今生虽不在这里评论, 但确实非常曲折精彩. 请有兴趣的自行了解.

不同于其他一些编程语言需要在编程前花点时间安装和设置, 比如Java. JavaScript编程是几乎可以立刻开始的, 只要你的电脑上装了一个网页浏览器. 火狐(Firefox), Chrome, IE都提供控制台(Console)功能. 本文将用Chrome. (起先用的是火狐, 但在控制台输入中文代码时, 发现它的代码提示功能和中文输入法有冲突)

打开控制台后, 上半部是输出, 取决于你当前打开的页面是什么, 内容也许是空白, 也许是一堆错误或者警告, 可以无视之, 以后就会都看懂的. 关键是下半部(默认高度只有一行), 有个 >> 的提示符号(其他浏览器可能是单个 >). 这里就是我们开始第一个程序的地方.

先问个好吧:
```
console.log("你好");
```
回车运行后, 可以看到输出部分除了重复这个程序, 还输出了这样两行(不同浏览器格式也许不同):
```
    你好
<-  undefined
```
"你好"是代码运行后打出的. <- 指向的是返回值. undefined的意思是没有返回任何值. 那怎样能返回一个值呢? 试试1+1:
```
1+1
```
运行后, 看到结果是:
```
<- 2
```
想知道二十年前就开始人人喊打的网络弹窗是怎样做的吗? 试试下面:
```
alert("确定要离开网站吗?");
```

扩展资料: 解释器与编译器的区别

