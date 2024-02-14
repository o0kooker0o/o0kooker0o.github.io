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
                <li><a href="https://blog.kooker.jp/http_image_filter_module/">使用Nginx裁剪图片 http_image_filter_module</a></li><li><a href="https://blog.kooker.jp/v2ex_sign_php_openshift/">v2ex的模拟登录以及自动签到_OpenShift</a></li><li><a href="https://blog.kooker.jp/MBC-The-Voice-Kids/">中东好童音</a></li><li><a href="https://blog.kooker.jp/%E6%B5%8B%E8%AF%95%E8%A7%86%E9%A2%91/">测试视频</a></li><li><a href="https://blog.kooker.jp/shell-file-exists/">Linux shell判断文件和文件夹是否存在</a></li><li><a href="https://blog.kooker.jp/k/">收藏夹</a></li><li><a href="https://blog.kooker.jp/redhat/">此内容被密码保护</a></li><li><a href="https://blog.kooker.jp/iphone-tool-tips/">iPhone快捷键集合</a></li><li><a href="https://blog.kooker.jp/Monkey-Story/">猴子的故事</a></li><li><a href="https://blog.kooker.jp/ScreenToGif/">ScreenToGif</a></li><li><a href="https://blog.kooker.jp/WinPE-DNS/">WinPE DNS</a></li><li><a href="https://blog.kooker.jp/%E7%BB%99WinPE%E5%AE%89%E8%A3%85%E7%BD%91%E5%8D%A1%E5%A3%B0%E5%8D%A1%E9%A9%B1%E5%8A%A8/">怎样给WinPE安装网卡声卡驱动</a></li><li><a href="https://blog.kooker.jp/Flush-Work-Under-Nginx/">Nginx 让 PHP Flush 工作</a></li><li><a href="https://blog.kooker.jp/OpenShift-PHP7-Install-Redis-GeoIP/">OpenShift PHP7扩展安装Redis &amp; GeoIP</a></li><li><a href="https://blog.kooker.jp/OpenShift-OpenResty-Install/">OpenShift OpenResty + LuaJIT安装脚本</a></li>            </ul>
        </section>
    
            <section class="widget">
            <h3 class="widget-title">最近回复</h3>
            <ul class="widget-list">
                                                    <li>
                        <a href="https://blog.kooker.jp/http_image_filter_module/comment-page-1#comment-22">kooker</a>: 航特你好，航特再见……                    </li>
                                    <li>
                        <a href="https://blog.kooker.jp/http_image_filter_module/comment-page-1#comment-21">红猫警长</a>: 。。。                    </li>
                                    <li>
                        <a href="https://blog.kooker.jp/%E8%99%8E%E6%AF%9B%E7%A3%81%E5%8A%9B%E7%A7%8D%E5%AD%90%E6%90%9C%E7%B4%A2/comment-page-1#comment-20">kooker</a>: 大王叫我来巡山&lt;source src=&quot;//cd...                    </li>
                                    <li>
                        <a href="https://blog.kooker.jp/%E8%99%8E%E6%AF%9B%E7%A3%81%E5%8A%9B%E7%A7%8D%E5%AD%90%E6%90%9C%E7%B4%A2/comment-page-1#comment-19">kooker</a>: 好的，喝茶去&lt;source src=&quot;//cdn...                    </li>
                                    <li>
                        <a href="https://blog.kooker.jp/%E8%99%8E%E6%AF%9B%E7%A3%81%E5%8A%9B%E7%A7%8D%E5%AD%90%E6%90%9C%E7%B4%A2/comment-page-1#comment-18">气味</a>: 你好，这位同志，铁观音，欢迎来喝茶。                    </li>
                                    <li>
                        <a href="https://blog.kooker.jp/free-clash/comment-page-1#comment-10">kooker</a>: 气总乃人神也！                    </li>
                                    <li>
                        <a href="https://blog.kooker.jp/free-clash/comment-page-1#comment-9">气味</a>: kooker真乃神人也！                    </li>
                                    <li>
                        <a href="https://blog.kooker.jp/OpenShift-PHP7-Install-Redis-GeoIP/comment-page-1#comment-3">kooker</a>: wget https://github.com/websuppo...                    </li>
                                    <li>
                        <a href="https://blog.kooker.jp/%E5%B0%8F%E7%BE%8E%E5%A5%B3%E5%BF%AB%E6%9D%A5%E7%8E%A9%E5%91%80/comment-page-1#comment-2">kooker</a>: 没有了                    </li>
                                    <li>
                        <a href="https://blog.kooker.jp/start/comment-page-1#comment-1">Typecho</a>: 欢迎加入 Typecho 大家族                    </li>
                            </ul>
        </section>
    
            <section class="widget">
            <h3 class="widget-title">分类</h3>
            <ul class="widget-list"><li class="category-level-0 category-parent"><a href="https://blog.kooker.jp/category/other/">Other</a></li><li class="category-level-0 category-parent"><a href="https://blog.kooker.jp/category/openshift/">OpenShift</a></li><li class="category-level-0 category-parent"><a href="https://blog.kooker.jp/category/PHP/">PHP</a></li><li class="category-level-0 category-parent"><a href="https://blog.kooker.jp/category/Nginx/">Nginx</a></li><li class="category-level-0 category-parent"><a href="https://blog.kooker.jp/category/%E7%BA%AF%E7%9C%9F%E9%9F%B3%E4%B9%90/">纯真音乐</a></li></ul>        </section>
    
            <section class="widget">
            <h3 class="widget-title">归档</h3>
            <ul class="widget-list">
                <li><a href="https://blog.kooker.jp/2016/05/">May 2016</a></li><li><a href="https://blog.kooker.jp/2016/04/">April 2016</a></li><li><a href="https://blog.kooker.jp/2016/03/">March 2016</a></li><li><a href="https://blog.kooker.jp/2016/02/">February 2016</a></li><li><a href="https://blog.kooker.jp/2016/01/">January 2016</a></li><li><a href="https://blog.kooker.jp/2015/12/">December 2015</a></li>            </ul>
        </section>
    
            <section class="widget">
            <h3 class="widget-title">其它</h3>
            <ul class="widget-list">
                                    <li class="last"><a href="https://blog.kooker.jp/admin/login.php">登录</a>
                    </li>
                                <li><a href="https://blog.kooker.jp/feed/">文章 RSS</a></li>
                <li><a href="https://blog.kooker.jp/feed/comments/">评论 RSS</a></li>
                <li><a href="https://typecho.org">Typecho</a></li>
            </ul>
        </section>
    
</div><!-- end #sidebar -->
