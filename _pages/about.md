---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Yang Luo. I received my B.S. degree in Mechanical Engineering from Central South University, Changsha, China, in 2025. I am currently pursuing my M.S. degree at the Shenyang Institute of Automation, Chinese Academy of Sciences. My current research interests include Robot Control.

## 🔥 News
{: #news}
* 2024.10: 🎉🎉 Our paper TREC is submitted to IEEE T-IM 2025!

## 📖 Educations
{: #educations}
* *2025.09 - present*, Master, The State Key Laboratory of Robotics at Shenyang Institute of Automation, Chinese Academy of Sciences, Shenyang, China.
* *2021.09 - 2025.06*, Undergraduate, Department of Mechanical Engineering, Central South University, Changsha, China.

## 📝 Publications
{: #publications}

<div class="publications-section">
{% for post in site.publications reversed %}
  {% include publication-card.html post=post %}
{% endfor %}
</div>
