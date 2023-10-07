---
title: 不用vpn，也能正常使用谷歌服务！2015 Google hosts 持续更新
author: 童远山
draft: fasle
date: 2015-11-03T01:50:22+00:00



categories:
  - 新闻
tags:
  - 上网技巧

---
**一共只要4步**

<ol id="index-ul">
  <li>
    <a title="找到hosts文件" href="#title-0">找到hosts文件</a>
  </li>
  <li>
    <a title="修改hosts" href="#title-1">修改hosts</a>
  </li>
  <li>
    <a title="让hosts立即生效" href="#title-2">让hosts立即生效</a>
  </li>
  <li>
    <a title="HOSTs文件下载地址" href="#title-3">HOSTs文件下载地址</a>
  </li>
</ol>

本方法对以下网站有效:

<p style="padding-left: 60px;">
  Google、谷歌学术、维基百科、ccFox.info、ProjectH、3DM、Battle.NET 、WordPress、Microsoft Live、GitHub、Box.com、SoundCloud、inoreader、Feedly、FlipBoard、Twitter、Facebook、Flickr、imgur、DuckDuckGo、Ixquick、Google Services、Google apis、Android、Youtube、Google Drive、UpLoad、Appspot、Googl eusercontent、Gstatic、Google other、Google Play等网站最新hosts。
</p>

&nbsp;

<p id="title-0">
  修改hosts的方法和下载地址如下：
</p>

## 1. 找到hosts这个文件 {#title-0}

### Windows 系统

是位于 C:\WINDOWS\system32\drivers\etc目录里。

### linux系统

请修改 /etc/hosts这个文件

### OSX苹果电脑

  1. 请打开你的文件管理器（也就是Finder）
  2. 然后，请按快捷键组合“Shift+Command+G”三个组合按键查找文件
  3. 并输入Hosts文件的所在路径：/etc/hosts
  4. 最后在打开的文件夹中找到“Hosts”文件夹

### 安卓（Android）手机用户

hosts文件路径：/system/etc/

## 2. 修改hosts文件 {#title-1}

### windows系统

以记事本的方式打开hosts，添加文章最后的下载文件中的地址并保存。

这样就可以了，注意hosts文件没有后缀。

### Linux、Mac

用户请用Notepad++ 转换文本编码和换行符格式。

### Android系统

  1. 直接用手机浏览器下载hosts文件（百度网盘里的，不带.txt后缀的）
  2. 用 RE管理器 （前提需要手机已Root）复制或者移动至 /system/etc/ 文件夹下
  3. 粘貼或者覆盖即可

### 3. 让hosts立即生效的方法 {#title-2}

### Windows

<p style="padding-left: 30px;">
  开始 -> 运行 -> 输入cmd
</p>

<p style="padding-left: 30px;">
  在CMD窗口输入: ipconfig /flushdns
</p>

### Linux

<p style="padding-left: 30px;">
  终端输入<br /> sudo rcnscd restar
</p>

### Mac OS X终端输入

<p style="padding-left: 30px;">
  sudo killall -HUP mDNSResponder
</p>

### Android

<p style="padding-left: 30px;">
  开启飞行模式 -> 关闭飞行模式
</p>

### 通用方法

<p style="padding-left: 30px;">
  拔网线(断网) -> 插网线(重新连接网络)
</p>

## 4.HOSTs文件下载地址 {#title-3}

http://pan.baidu.com/s/1jGjgrhc