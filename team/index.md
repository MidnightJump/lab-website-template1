---
title: 团队
nav:
  order: 3
  tooltip: 关于我们的团队
---

# {% include icon.html icon="fa-solid fa-users" %}团队

我们的团队由经验丰富的研究人员、充满激情的学生和专业的工程师组成。我们欢迎来自不同背景的人才加入我们的研究团队，共同推动科技进步。

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

我们致力于创建一个开放、协作的研究环境，鼓励创新思维和跨学科合作。团队成员来自世界各地，带来了丰富的文化背景和专业知识。

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
