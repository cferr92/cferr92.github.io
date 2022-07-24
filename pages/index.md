---
layout: default
permalink: /
---

{% include landing.html %}
<p class="text-center">{% include elements/button.html link="https://github.com/" text="Resume PDF" %}</p>
# **About Me**

Hi, I am **{{ site.author.name }}** :wave:<br>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

<div class="row">
{% include about/timeline.html %}
</div>
---
<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Design Skills" source=site.data.design-skills %}
</div>