---
title: Home
---

<div> 
    <img src="{{ "/images/nerdy2matologo.jpg" | absolute_url }}" alt="nerdy2matologo" style="width:20%;" >
</div>

# Hi,

My name is Rachel Huang (or you can call me Nerdy2mato). I am a data scientist.

I love learning statistics, machine learning and coding. I started teaching myself since four years ago. Recently, I decided to share what I have learned along the way because I believe that the best way of learning is to share what you have learned.

On this site, I will be writing [blogs](https://rachelqhuang.github.io/blogs) about everything I have learned that I think worth sharing. I will also include my projects using machine learning. I also love reading statistical books. I will write reviews about the books I read.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>