目的

	找前端工作
	会前端
	学前端

# 找前端工作

理解这个工作是什么，谁招人，招什么人

看职位介绍

1. 前端开发，移动端页面开发，微信端、APP端的移动Web、微信小程序、PC WebApp, 熟悉跨浏览器(就是兼容问题)、跨终端（PC/android/iOS）的开发
2. HTML5、CSS3，熟悉JavaScript, Ajax
3. NodeJS  -> JavaScript
4. JQuery、Bootstrap、React 框架（framework）
5. HTTP协议/网络协议
6. github -> git 版本控制
7. 数据可视化 http://www.chartjs.org 
8. 实际项目开发
9. markdown
10. linux

# 问题解答

## 1.什么是框架

```javascript
// 等价的
// 原生代码
var x = document.getElementById('submit');
x.style.display = "hidden";

// jquery代码
$("#submit").hide();
```

框架分好多种，比较典型的有

### 封装型框架

像jquery这种，对原生代码进行了封装，提高JS的易用性（提高开发效率）

为什么要提高易用性，因为前端的易用性很差

为什么差呢，因为不同的浏览器，对同样的代码有不同的解释，这个就叫兼容性问题

比如，同一个代码，在chrome、firefox，IE 6/7/8/9/10，edage等浏览器中，表现是不一样的，这个兼容性问题

相对学习成本低

`jquery/bootstrap`

### 结构型框架

有自己的规则，有一定的学习成本，与原生代码或者这种封装的框架看起来差别很大，相对学习成本更高

angular/backbone/react

## 2.HTML5和HTML的区别，CSS和CSS3有什么区别

自己百度吧

## Ajax

访问一个网页，网页就要刷新

假如一个网页中，有很多东西，但是我只想更新其中的一小部分

那如果这样我还全部网页刷新的话，是不是很浪费流量

那我们能不能只刷新这一小部分的数据，答案是可以的，所以就有了Ajax技术

## HTTP协议

header, 服务端怎么接受请求，写一个小的服务器来理解一下

什么是POST/GET，HTTP里面的session，cookie

网络协议 HTTPS、HTTP、RPC

## 版本控制，git/github

给你代码，增加了一个版本的功能，比如1.0/2.0/3.0，方便迭代开发，如果出了问题，可以回到以前的版本

不同的人合作写代码，不用复制来复制去

## 数据可视化

后端把数据，你用图片等方式在前端展示出来，都有现成的框架，有些情况需要改框架来自己定制

## 实际项目开发

自己写点代码

## markdown

很简单

## GIT如何安装使用

https://git-scm.com/download/win

看PPT