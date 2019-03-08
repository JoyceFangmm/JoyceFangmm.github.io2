---
layout: post
title:  "【译】macOS快速隐藏/展示隐藏文件"
date:   2019-03-08 15:00:00 +0800
categories: tool 译
tags: tool 译
header-style: text
---


>
> 截取翻译自[@lanLunn](https://twitter.com/IanLunn/)的[Quickly Show/Hide Hidden Files on macOS Sierra, OS X El Capitan & Yosemite](https://ianlunn.co.uk/articles/quickly-showhide-hidden-files-mac-os-x-mavericks/)
>
> 选取了其中两种比较快捷的方法作记录，方便后期查阅

# 最快速的方法

限制：必须是 macOS Sierra +

`CMD + SHIFT + .`


# 非快速方法

展示隐藏文件

1.  打开终端，输入
{% highlight bash %}
defaults write com.apple.finder AppleShowAllFiles YES
{% endhighlight %}
2.  然后`return`
3.  重启`Finder`

隐藏操作流程一样，只需要替换指令
{% highlight bash %}
defaults write com.apple.finder AppleShowAllFiles NO
{% endhighlight %}
