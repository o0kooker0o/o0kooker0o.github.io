---
layout: default
---	

<div class="col-mb-12 col-8" id="main" role="main">
{% for post in site.posts limit:8 %}
            <h2 class="post-title" itemprop="name headline">
                <a itemprop="url"
                   href="{{ post.url }}">{{ post.title }}</a>
            </h2>
        <ul class="post-meta">
            <li itemprop="author" itemscope itemtype="http://schema.org/Person">
                作者:{{ site.author.name }}
            </li>
            <li>时间: <time datetime="{{ post.date | date:"%b %e, %Y" }}" itemprop="datePublished">{{ post.date | date:"%b %e, %Y" }}</time>
            </li>
        </ul>
            <div class="post-content" itemprop="articleBody">
		<blockquote>{{ post.description }}</blockquote>
			{% endfor %}</div>

<div class="col-mb-12 col-offset-1 col-3 kit-hidden-tb" id="secondary" role="complementary">
            <section class="widget">
            <h3 class="widget-title">最新文章</h3>
            <ul class="widget-list">
		{% for post in site.posts limit: 10 %}
                <li><a href="{{ production_url }}{{ post.url }}" title="{{ post.title | escape }}">{{ post.title }}</a></li>
      		{% endfor %}
         	</ul>
		</section>

            <section class="widget">
            <h3 class="widget-title">归档</h3>
            <ul class="widget-list">

                </ul>
        </section>
    
            <section class="widget">
            <h3 class="widget-title">其它</h3>
            <ul class="widget-list">
                <li class="last"><a href="https://bbs.kooker.jp/">BBS</a></li>
                <li><a href="https://cdn.kooker.jp/feed/">CDN</a></li>
                <li><a href="https://docs.kooker.jp/">DOCS</a></li>
            </ul>
        </section>
    
</div><!-- end #sidebar -->