---
layout: post
title: "hello jekyll"
description: ""
category: 
tags: []
---
{% include JB/setup %}
## 第一页，jekyll的开始

Jekyll is a parsing engine bundled as a ruby gem used to build static websites from
dynamic components such as templates, partials, liquid code, markdown, etc. Jekyll is known as "a simple, blog aware, static site generator".

### 博客文章：[用Jekyll构建基于bootstrap系统](http://#)

程序员会写程序是基本技能，程序员会写文档是更高的能力。用简单的图形表达架构，用流畅语言描述业务，用专业的文笔写成报告，看似简单的要求，但对于普通的程序员来说都是一种挑战。

有时候我们纠结的不是怎么组织文字，而是怎么排版，用哪种字体，居中还是靠右放置？如何能保持多人撰写文档的统一风格？

Jekyll可以帮助我们标准化文档结构，文档样式，文档过程。剩下就是提升自己的知识基础了。

### 测试语法高亮

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

{% highlight ruby linenos  %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}
