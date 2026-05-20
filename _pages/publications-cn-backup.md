---
layout: archive
title: "论文发表"
permalink: /publications-cn/
author_profile: true
---

{% include base_path %}

{% if site.author.googlescholar %}
  <div class="wordwrap">您也可以在 <a href="{{site.author.googlescholar}}">我的 Google Scholar 个人主页</a> 上找到我的论文。</div>
{% endif %}

{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title | replace: 'Books', '著作' | replace: 'Journal Articles', '期刊论文' | replace: 'Conference Papers', '会议论文' | replace: 'Preprints', '预印' | replace: 'Under Review', '暂未发表' }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
