---
layout: post
title:  "Welcome to Jekyll!"
date:   2017-12-18 16:57:52 +0100
categories: jekyll update
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nosti, credo, illud: Nemo pius est, qui pietatem-; Nemo nostrum istius generis asotos iucunde putat vivere. Quamvis enim depravatae non sint, pravae tamen esse possunt. Tum mihi Piso: Quid ergo? Quae quidem sapientes sequuntur duce natura tamquam videntes; Atqui pugnantibus et contrariis studiis consiliisque semper utens nihil quieti videre, nihil tranquilli potest.

<script id="algolia__template" type="text/template">
<article id="content" class="algolia__result post" itemscope itemtype="https://schema.org/BlogPosting">
    {{#posted_at}}
    <header>
        <span class="p-date algolia__result-date">{{ posted_at_readable }}</span>
    </header>
    
    <h1 class="post-title"><a class="algolia__result-link" href="{{ full_url }}">{{{ _highlightResult.title.value }}}</a></h1>
    <div class="algolia__result-text post-content">{{{ _highlightResult.text.value }}}</div>
</article>
</script>