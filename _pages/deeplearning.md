---
layout: single
title: "Deeplearning record"
permalink: /deeplearning/
author_profile: true
---

# Preface 
In the recent past, I have been recording my study notes in Notion. To facilitate my own review and organization later on, I will regularly organize the content here, which is also a form of open-source, allowing everyone to review the content written by the author (a beginner). Since it is a beginner's study, the learning content is for reference only. : ) 
<div style="text-align: Right;">
  2024.12.16 by Gain
</div>


* I will share and record my learning process in two ways: 

  1. notion draft notes：[notion shared link](https://protective-morning-0bc.notion.site/129ee0e60378803ebfd6fa988800257f?pvs=4)
  2. Stage-by-stage organization is carried out on this website.


## Table of Contents

{% for item in site.deeplearning %}
  <div style="display: flex; justify-content: space-between; align-items: center;">
    <h2 style="margin: 0;">
      <a href="{{ item.url }}">{{ item.title }}</a>
    </h2>
    <span style="font-size: 0.9em; color: gray;">{{ item.date | date: "%Y-%m-%d" }}</span>
  </div>
{% endfor %}

