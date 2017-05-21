---
layout: page
title: ""
date: 
modified:
excerpt:
image:
  feature:
search_omit: true
sitemap: false
---
  
<!-- Search form -->
<form method="get" action="{{ site.url }}/search/" data-search-form class="simple-search">
  <input type="search" name="q" id="q" placeholder="What are you looking for?" data-search-input id="goog-wm-qt" autofocus />
  <input type="submit" value="Go" id="goog-wm-sb" />
</form>

<!-- Search results placeholder -->
<h6 style = "color:#BC2A0A;" data-search-found>
  <span data-search-found-count></span> result(s) found for &ldquo;<span data-search-found-term></span>&rdquo;.
</h6>
<ul class="post-list" data-search-results></ul>

<!-- Search result template -->
<script type="text/x-template" id="search-result">
  <li><article>
    <a href="##Url##">##Title## <span class="excerpt">##Excerpt##</span></a>
  </article></li>
</script>
