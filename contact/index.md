---
title: 联系
nav:
  order: 6
  tooltip: 邮件、电话、地址
---

# {% include icon.html icon="fa-regular fa-envelope" %}联系我们

狼牙战队欢迎所有热爱机器人的同学加入！

湖北省武汉市洪山区珞喻路 1037 号
华中科技大学智能互联网湖北省重点实验室

{%
  include button.html
  type="email"
  text="hustrobomaster@163.com"
  link="hustrobomaster@163.com"
%}

{%
  include button.html
  type="address"
  tooltip="我们实验室的地址"
  link="https://surl.amap.com/1vpaONXCHaR5"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
