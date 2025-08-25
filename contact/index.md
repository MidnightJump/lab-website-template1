---
title: 联系我们
nav:
  order: 5
  tooltip: 邮箱、地址和位置
---

# {% include icon.html icon="fa-regular fa-envelope" %}联系我们

如果您对我们的研究感兴趣，想要加入我们的团队，或者有任何合作意向，欢迎通过以下方式与我们联系。我们期待与您建立联系！

{%
  include button.html
  type="email"
  text="contact@MidnightJump.com"
  link="contact@MidnightJump.com"
%}
{%
  include button.html
  type="phone"
  text="+86-xxx-xxxx-xxxx"
  link="+86-xxx-xxxx-xxxx"
%}
{%
  include button.html
  type="address"
  tooltip="我们的位置，方便导航"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="实验室环境"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="研究设备"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
**实验室地址**  
[详细地址信息]  
[城市，省份，邮编]
{% endcapture %}

{% capture col2 %}
**办公时间**  
周一至周五: 9:00-18:00  
周末: 预约开放
{% endcapture %}

{% capture col3 %}
**联系方式**  
邮箱: contact@MidnightJump.com  
电话: +86-xxx-xxxx-xxxx
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
