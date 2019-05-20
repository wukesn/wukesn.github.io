---
layout: page
title: "关于"
permalink: about.html
image: /public/images/c2.jpg
color: '#f44336'
sequence: 9
---


{% comment %}
  This inserts the "about" photo and text from `_config.yml`.
  You can edit it there (jekyll needs restart!) or remove it and provide your own photo/text.
  Don't forget to add the `me` class to the photo, like this: `![alt](src){:.me}`.
{% endcomment %}

{% if site.author.photo %}
  ![{{site.author.name}}]({{site.author.photo}}){:.me}
{% endif %}


我是<u>木槿暖夏、</u>，从事 IT 行业。我喜爱编程、了解最新技术、音乐、电影等等。


## 更加了解我

我在[GitHub](https://github.com/wukesn) 上维护我的代码以及关注开源项目，你还可以在 [Linkedin](https://www.linkedin.com/in/%E7%8F%82-%E5%90%B4-3913ab187/)上找到我。


## 为什么要写这个博客？

花时间进行写作是一件很有意义也很值得去做的事。我希望能在这里来分享技术、记录生活，同时也希望能结交到更多朋友。

## 联系我

请发邮件到 [{{site.author.email}}](mailto:{{site.author.email}}) 与我联系。你也可以通过页面左下角的链接给我留言。
