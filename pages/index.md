---
layout: default
permalink: /
---

{% include landing.html %}
# **About Me**

Hi, I'm **{{ site.author.name }}** :wave:<br>

I am a digital investigator with years of experience working in social media, analytics, and information technology - oftentimes all at the same time!

Currently, I work for Ethos Risk Services, delivering accurate and timely investigations to a wide range of Fortune 500 clients. Previously, I worked as a multidisciplined analyst at the National Security Agency (NSA) and am a graduate of Florida International University with a double major in Asian Studies and Sociology, a minor in Social Media and E-Marketing Analytics, and experience in both Japanese and Mandarin Chinese.

In my free time, I produce video game content for a small network of YouTube channels and have been doing so since 2011. In 2013, I began writing about video games as a freelancer and have since published over five hundred reviews, news, and other features for my own website and others.

I am always open to learning more and connecting with others, just shoot me an email!

<p class="text-center">{% include elements/button.html link="mailto:cferr92@gmail.com" text="Contact me" block=true %}</p>
<p class="text-center">{% include elements/button.html link="/assets/Resume.pdf" text="Resume PDF" block=true %}</p>

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