---
layout: default
permalink: /
---

{% include landing.html %}
# **About Me**

Hi, I'm **{{ site.author.name }}** :wave:<br>
I am a recent graduate of Florida International University with a double major in Asian Studies and Sociology and minor in Social Media and E-Marketing Analytics. I have over two years of Japanese language study experience and am currently attending classes for Chinese.

Graduating in December 2020, I am now looking to apply my knowledge and skills to the fields of journalism, social research, digital media, and/or foreign relations. I am specifically interested in staff writing/editing, digital media specialist, social media specialist, and analyst positions.

I am currently self-employed and produce video game content for a small network of YouTube channels that I have been operating since 2011. In 2013, I began writing about video games as a freelancer and have since published over five hundred reviews, news, and other features for my own website and others. 

<p class="text-center">{% include elements/button.html link="mailto:cferr92@gmail.com" text="Contact me" block=true %}</p>
<p class="text-center">{% include elements/button.html link="https://github.com/" text="Resume PDF" block=true %}</p>

<div class="row">
{% include about/timeline.html %}
</div>
---
<div class="row">
{% include about/skills.html title="Languages" source=site.data.languages %}
{% include about/skills.html title="Tech Skills" source=site.data.tech-skills %}
</div>
<div class="row">
{% include about/skills.html title="Design Skills" source=site.data.design-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>