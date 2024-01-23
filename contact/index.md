---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

{%
  include button.html
  type="email"
  text="jmei@hit.edu.cn"
  link="jmei@hit.edu.cn"
%}
{%
  include button.html
  type="phone"
  text="(0755) 86102664"
  link="+86-0755-86102664"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com.hk/maps/place/%E5%93%88%E5%B0%94%E6%BB%A8%E5%B7%A5%E4%B8%9A%E5%A4%A7%E5%AD%A6(%E6%B7%B1%E5%9C%B3)/@22.586345,113.9683681,15z/data=!4m2!3m1!1s0x0:0x44719e686b463d1d?sa=X&ved=2ahUKEwji4saJv9KCAxXJF4gKHZuoC7MQ_BJ6BAhNEAA&cshid=1700480585927273"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/HITSZ/HITSZ1.jpg"
  caption="Harbin Institute of Technology, Shenzhen"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/HITSZ/HITSZ2.jpg"
  caption="Harbin Institute of Technology, Shenzhen"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Harbin Institute of Technology, Shenzhen
{% endcapture %}

{% capture col2 %}
School of Mechanical Engineering and Automation
{% endcapture %}

{% capture col3 %}
Multi-Agent System Lab
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
