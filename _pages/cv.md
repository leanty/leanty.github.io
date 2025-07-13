---
layout: archive
title: "简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育经历
======
* 版本控制理论博士，GitHub 大学，2018（预计）
* Jekyll 硕士，GitHub 大学，2014
* GitHub 学士，GitHub 大学，2012

工作经历
======
* 2024年春：Academic Pages 合作者
  * GitHub 大学
  * 职责：模板更新与改进
  * 导师：用户

* 2015年秋：研究助理
  * GitHub 大学
  * 职责：合并 pull request
  * 导师：Hub 教授

* 2015年夏：研究助理
  * GitHub 大学
  * 职责：标签管理
  * 导师：Git 教授
  
技能
======
* 技能1
* 技能2
  * 子技能2.1
  * 子技能2.2
  * 子技能2.3
* 技能3

发表成果
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
演讲
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
教学
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
服务与领导力
======
* 当前已登录 43 个不同的 Slack 团队
