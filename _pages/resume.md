---
permalink: /
title: "个人简历"
excerpt: "Resume"
author_profile: true
---

{% include base_path %}

**徐潇源（Xiaoyuan Xu）：上海交通大学电子信息与电气工程学院电气工程系长聘教轨副教授**<br/>[[学校官网个人主页]](https://eei.sjtu.edu.cn/faculty-detail.php?id=91)

```
 现招收2022级硕士研究生
```

主要研究方向
------
* __电力系统不确定性分析__
  * 新能源发电建模、感知与预测
  * 高比例新能源电力系统分析与计算
  * 高比例新能源电力系统优化运行：随机/鲁棒/分布鲁棒/数据驱动优化
* __配电网-交通网的耦合与协调优化__
  * 大规模电动汽车灵活调度
  * 交通系统建模与分析
  * 配电网-交通网联合规划与运行

工作经历
------
* 2022.01-现在&ensp;&ensp;&ensp;&nbsp;&nbsp;**长聘教轨副教授**
  * 上海交通大学&nbsp;&nbsp;电子信息与电气工程学院电气工程系
  
* 2018.10-2021.12&nbsp;&nbsp;**助理教授**
  * 上海交通大学&nbsp;&nbsp;电子信息与电气工程学院电气工程系

* 2017.05-2018.05&nbsp;&nbsp;**访问学者**
  * 美国伊利诺伊理工大学&nbsp;&nbsp;Robert W. Galvin Center for Electricity Innovation

* 2016.06-2018.10&nbsp;&nbsp;**博士后**
  * 上海交通大学&nbsp;&nbsp;电子信息与电气工程学院

学习经历
------
* 2010.09-2016.06&nbsp;&nbsp;上海交通大学&nbsp;&nbsp;电气工程&nbsp;&nbsp;**博士**
* 2006.09-2010.06&nbsp;&nbsp;上海交通大学&nbsp;&nbsp;电气工程&nbsp;&nbsp;**学士**

学术论著 [<img src="images/skip_to.jpg" width="20" alt="详细情况" />](/publications)
------

  <blockquote> <p>专著</p> </blockquote>
  <ol>
  {% for post in site.publications reversed %}
  {% if post.type == "book" %}
    {% if post.corresponding %}
	  {% include archive-single-cv.html %}
	{% endif %}
  {% endif %}
  {% endfor %}
  
  {% for post in site.publications reversed %}
  {% if post.type == "book" %}
    {% if post.corresponding %}
	{% else %}
	  {% include archive-single-cv.html %}
	{% endif %}
  {% endif %}
  {% endfor %}
  </ol>

  <blockquote> <p>英文期刊论文</p> </blockquote>
  <ol>
  {% for post in site.publications reversed %}
  {% if post.type == "journal-en" %}
    {% if post.corresponding %}
	  {% include archive-single-cv.html %}
	{% endif %}
  {% endif %}
  {% endfor %}
  
  {% for post in site.publications reversed %}
  {% if post.type == "journal-en" %}
    {% if post.corresponding %}
	{% else %}
	  {% include archive-single-cv.html %}
	{% endif %}
  {% endif %}
  {% endfor %}
  </ol>

  <blockquote> <p>中文期刊论文</p> </blockquote>
  <ol>
  {% for post in site.publications reversed %}
  {% if post.type == "journal-zh" %}
    {% if post.corresponding %}
	  {% include archive-single-cv.html %}
	{% endif %}
  {% endif %}
  {% endfor %}
  
  {% for post in site.publications reversed %}
  {% if post.type == "journal-zh" %}
    {% if post.corresponding %}
	{% else %}
	  {% include archive-single-cv.html %}
	{% endif %}
  {% endif %}
  {% endfor %}
  </ol>
<!--
  <blockquote> <p>中文期刊论文</p> </blockquote>
  <ol>
  {% for post in site.publications reversed %}
  {% if post.type == "conference-en" %}
    {% if post.corresponding %}
	  {% include archive-single-cv.html %}
	{% endif %}
  {% endif %}
  {% endfor %}
  
  {% for post in site.publications reversed %}
  {% if post.type == "conference-en" %}
    {% if post.corresponding %}
	{% else %}
	  {% include archive-single-cv.html %}
	{% endif %}
  {% endif %}
  {% endfor %}
  </ol>
-->
  
学术报告 [<img src="images/skip_to.jpg" width="20" alt="详细情况" />](/talks)
------
  <ol>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ol>

科研项目 [<img src="images/skip_to.jpg" width="20" alt="详细情况" />](/projects)
------
   {% include_relative projects/projects_content.html %}

专利 [<img src="images/skip_to.jpg" width="20" alt="详细情况" />](/patents)
------
  <ol>{% for post in site.posts reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ol>

荣誉奖励 [<img src="images/skip_to.jpg" width="20" alt="详细情况" />](/prizes)
------
   {% include_relative prizes/prizes_content.md %}

社会兼职 [<img src="images/skip_to.jpg" width="20" alt="详细情况" />](/positions)
------
   {% include_relative positions/positions_content.md %}
  
课程教学 [<img src="images/skip_to.jpg" width="20" alt="详细情况" />](/teaching)
------
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

研究生 [<img src="images/skip_to.jpg" width="20" alt="详细情况" />](/graduates)
------
   {% include_relative graduates/graduates_content.html %}