---
layout: default
permalink: /
---

{% include landing.html %}
<p class="text-center">{% include elements/button.html link="https://github.com/" text="Resume PDF" block=true %}</p>
# **About Me**

Hi, I am **{{ site.author.name }}** :wave:<br>
I am a recent graduate of Florida International University with a double major in Asian Studies and Sociology and minor in Social Media and E-Marketing Analytics. I have over two years of Japanese language study experience and am currently attending classes for Chinese.<hr>

Graduating in December 2020, I am now looking to apply my knowledge and skills to the fields of journalism, social research, digital media, and/or foreign relations. I am specifically interested in staff writing/editing, digital media specialist, social media specialist, and analyst positions.<hr>

I am currently self-employed and produce video game content for a small network of YouTube channels that I have been operating since 2011. In 2013, I began writing about video games as a freelancer and have since published over five hundred reviews, news, and other features for my own website and others. 

<div class="row">
{% include about/timeline.html %}
</div>
---
<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Design Skills" source=site.data.design-skills %}
</div>