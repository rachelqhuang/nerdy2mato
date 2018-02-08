---
title: Home
---

<div> 
    <img src="{{ "/images/nerdy2matologo.jpg" | absolute_url }}" alt="nerdy2matologo" style="width:45%;" >
</div>

# Build a Website with Jekyll and GitHub Pages 

With [GitHub pages](https://pages.github.com/) and [Jekyll](https://jekyllrb.com/) you can quickly create and publish a website for free! 
It is an ideal solution for creating a simple project or personal site to highlight your academic work. 

This workshop will introduce the basics of using the popular static website generator Jekyll integrated with GitHub pages. 
You will learn how to set up a project repository, write content in Markdown, and publish your site, all using GitHub's user friendly web interface. 
Advanced usage of Jekyll for local web development is introduced final section.

Watch [workshop screen cast](https://youtu.be/SWVjQsvQocA) for full content.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>