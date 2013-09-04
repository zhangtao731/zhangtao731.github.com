---
layout: name
title: Home
section: Home
---

欢迎
=======

<img class='inset right' src='/images/ouyangm.jpeg' title='阳志平' alt='阳志平' width='100px' />
阳志平，男，80年代初出生于湖南，现居北京。

希望将有限的生命浪费在原创、具备美感、与众不同的事情上，如果加一个专业限定，那就是心理健康与认知科技领域。我相信，理解人类的大脑及行为与走向太空一样重要。欢迎你订阅我的[网志](/feed)以及[与我联系](http://www.yangzhiping.com/info/contact.html)。

<div class='section'>  
<h1 id='id174'>网志</h1>
<p><a href='/psy'>随笔</a>栏目主要记录一些思考，以心理学，创业，读书为主。</p> 
{% for post in site.categories.psy limit:3 %}
<ul class="compact recent">
<li>
	<a href="{{ post.url }}" title="{{ post.excerpt }}">{{ post.title }}</a>
	<span class="date">{{ post.date | date_to_string }}</span> 
</li>
</ul>
{% endfor %}
</div>

<div class='section'> 
<p><a href='/tech'>技术</a>栏目主要记录一些技术细节，以Ruby，R为主。</p> 
{% for post in site.categories.tech limit:3 %}
<ul class="compact recent">
<li>
	<a href="{{ post.url }}" title="{{ post.excerpt }}">{{ post.title }}</a>
	<span class="date">{{ post.date | date_to_string }}</span> 
</li>
</ul>
{% endfor %}
</div>

<div class='section'>
<h1 id='id175'>演讲</h1>

<p>心理学与现代科技的交互，会诞生一些什么？这是一些keynote与ppt:</p>
<ul class='compact recent'>
<li>
    <a href='http://www.tedtochina.com/2009/10/29/mind2/'>从人类2.0到心智2.0：关于积极心理学的分享（2009-10-29）</a>
</li>
<li>
    <a href='http://www.yangzhiping.com/psy/brain-fit.html'>脑训练与心理战（2009-7）</a>
</li>
<li>
    <a href='http://www.slideshare.net/ouyangzhiping/ss-1175425'>中国人的婚恋行为（2007-05-25）</a>
</li>
</ul></div>

<div class='section'>
<h1 id='id176'>图书</h1>

<p>我主编、翻译与审校的图书。</p>

<p><a href='psy/taking-the-measure-of-work.html'><img src='/images/book/book1-small.jpg' alt='工作评价' width='100px' /></a><a href='psy/disaster-psychology.html'><img src='/images/book/book2-small.jpg' alt='灾后心理自助手册' width='100px' /></a><a href='psy/xingfuke.html'><img src='/images/book/book3-small.jpg' alt='积极心理学团体活动课操作指南' width='100px' /></a><a href='psy/snabook.html'><img src='/images/book/snabook-small.png' alt='snabook' width='100px' /></a></p>
</div>
</div>
