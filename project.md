---
layout: page
title: Project
subtitle: Discover our project
cover-img: https://gohu00.github.io/gemmes_vn/assets/img/path.jpg
i18n-link: project
lang: en


modules:
  - name: Mekong
    desc: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sed sapien dignissim, consectetur tellus ultrices, ultricies orci.
    url: https://gohu00.github.io/gemmes_vn/mekong/
    img: https://gohu00.github.io/gemmes_vn/assets/img/avatar-icon.png
  - name: Health
    desc: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sed sapien dignissim, consectetur tellus ultrices, ultricies orci.
    url: https://gohu00.github.io/gemmes_vn/health/
    img: https://gohu00.github.io/gemmes_vn/assets/img/avatar-icon.png
  - name: Migration
    desc: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sed sapien dignissim, consectetur tellus ultrices, ultricies orci.
    url: https://gohu00.github.io/gemmes_vn/migration/
    img: https://gohu00.github.io/gemmes_vn/assets/img/avatar-icon.png

---


<style>
#more {display: none;}

.button {
  background-color: #da291c;
  border: none;
  color: white;
  padding: 5px 3px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}


.button2 {
  background-color: "#F5F5F5";
  border-bottom: "#EAEAEA";
  font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif;
  border: none;
  color: white;
  padding: 5px 3px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}
</style>

### Project


Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque malesuada mi ac nibh fermentum, ut commodo ligula lacinia. Morbi faucibus, dui sit amet laoreet ultrices, lectus eros pretium augue, in consectetur massa lectus eu lectus. Suspendisse scelerisque sagittis arcu eget facilisis. Aenean ornare cursus urna nec ultrices. Donec quis ornare felis. Morbi viverra vitae ligula quis lacinia. Pellentesque tempor porta eleifend. Ut at nisl eget ligula tempus aliquet vitae vitae magna. Nulla eget neque pellentesque, gravida sapien sit amet, pellentesque magna. Ut orci erat, posuere et elit id, hendrerit interdum ex. Sed varius aliquet justo, vel tempus sapien tristique sit amet.

Phasellus mollis eros lectus, nec vestibulum massa faucibus vel. Duis auctor ex est. Nulla nec egestas orci, commodo semper nisl. Fusce nec odio viverra, malesuada tortor in, varius lectus. Proin eget purus pretium, vulputate turpis sit amet, dignissim nulla. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Sed tincidunt diam eget diam eleifend, vel egestas felis laoreet. Phasellus sed vulputate eros, quis consectetur tellus. Phasellus blandit libero ullamcorper lorem scelerisque blandit. Sed vel diam eleifend, placerat lorem ac, sollicitudin nunc.

Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Morbi sed tortor mollis, faucibus ligula ut, maximus odio. Duis tortor libero, scelerisque in mauris ut, pulvinar hendrerit sapien. Mauris luctus augue et enim gravida, ac vulputate arcu placerat. Nulla facilisi. Cras arcu erat, tempus id tortor sed, viverra viverra neque. Sed aliquam leo mollis ligula auctor, at maximus nisi posuere. Curabitur sed pharetra quam. Nullam egestas neque ipsum, eget aliquet ex congue nec. Morbi turpis nisl, accumsan et nisi et, consequat ullamcorper lectus. 

<h2>Research package n°1</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus imperdiet, nulla et dictum interdum, nisi lorem egestas vitae scelerisque enim ligula venenatis dolor.<span id="dots"></span>
<div id="more">
<h3>Related subjects</h3>
{% include list-circles.html items=page.modules %} 

Maecenas nisl est, ultrices nec congue eget, auctor vitae massa. Fusce luctus vestibulum augue ut aliquet. Nunc sagittis dictum nisi, sed ullamcorper ipsum dignissim ac. In at libero sed nunc venenatis imperdiet sed ornare turpis. Donec vitae dui eget tellus gravida venenatis. Integer fringilla congue eros non fermentum. Sed dapibus pulvinar nibh tempor porta.

<h3>Latest news of the research package</h3>

{% assign posts = paginator.posts | default: site.posts  %}

<div class="post-list">
	 {% for post in posts %}
	  {% if post.lang == page.lang %}
	  <article class="post-preview">
		<a href="{{ post.url | absolute_url  }}">
		<h2 class="post-title">{{ post.title }}</h2>

	   {% if post.subtitle %}
        <h3 class="post-subtitle">
        {{ post.subtitle }}
        </h3>
		{% endif %}
		</a>

    <p class="post-meta">
      {% assign date_format = site.date_format | default: "%B %-d, %Y" %}
      Posted on {{ post.date | date: date_format }}
    </p>

    <!-- <div class="post-entry-container"> -->
      <!-- {%- capture thumbnail -%} -->
        <!-- {% if post.thumbnail-img %} -->
          <!-- {{ post.thumbnail-img }} -->
        <!-- {% elsif post.cover-img %} -->
          <!-- {% if post.cover-img.first %} -->
            <!-- {{ post.cover-img[0].first.first }} -->
          <!-- {% else %} -->
            <!-- {{ post.cover-img }} -->
          <!-- {% endif %} -->
        <!-- {% else %} -->
        <!-- {% endif %} -->
      <!-- {% endcapture %} -->
      <!-- {% assign thumbnail=thumbnail | strip %} -->
      <!-- {% if thumbnail != "" %} -->
      <!-- <div class="post-image"> -->
        <!-- <a href="{{ post.url | absolute_url }}"> -->
          <!-- <img src="{{ thumbnail | absolute_url }}"> -->
        <!-- </a> -->
      <!-- </div> -->
      <!-- {% endif %} -->
      <div class="post-entry">
        {% assign excerpt_length = site.excerpt_length | default: 50 %}
        {{ post.excerpt | strip_html | xml_escape | truncatewords: excerpt_length }}
        {% assign excerpt_word_count = post.excerpt | number_of_words %}
        {% if post.content != post.excerpt or excerpt_word_count > excerpt_length %}
          <a href="{{ post.url | absolute_url }}" class="post-read-more">[Read&nbsp;More]</a>
        {% endif %}
      </div>
    

    {% if post.tags.size > 0 %}
    <div class="blog-tags">
      Tags:
      {% if site.link-tags %}
      {% for tag in post.tags %}
      <a href="{{ '/tags' | absolute_url }}#{{- tag -}}">{{- tag -}}</a>
      {% endfor %}
      {% else %}
        {{ post.tags | join: ", " }}
      {% endif %}
    </div>
    {% endif %}

   </article>
	 {% endif %} 
    {% endfor %}
 
</div>

{% if paginator.total_pages > 1 %}
<ul class="pagination main-pager">
  {% if paginator.previous_page %}
  <li class="page-item previous">
    <a class="page-link" href="{{ paginator.previous_page_path | absolute_url }}">&larr; Newer Posts</a>
  </li>
  {% endif %}
  {% if paginator.next_page %}
  <li class="page-item next">
    <a class="page-link" href="{{ paginator.next_page_path | absolute_url }}">Older Posts &rarr;</a>
  </li>
  {% endif %}
</ul>
{% endif %}

</div>
<button class="button" onclick="myFunction()" id="myBtn">Read more</button>


<h2>Research package n°2</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus imperdiet, nulla et dictum interdum, nisi lorem egestas vitae scelerisque enim ligula venenatis dolor.<span id="dots"></span>
<div id="more">
<h3>Related subjects</h3>
{% include list-circles.html items=page.modules %} 

Maecenas nisl est, ultrices nec congue eget, auctor vitae massa. Fusce luctus vestibulum augue ut aliquet. Nunc sagittis dictum nisi, sed ullamcorper ipsum dignissim ac. In at libero sed nunc venenatis imperdiet sed ornare turpis. Donec vitae dui eget tellus gravida venenatis. Integer fringilla congue eros non fermentum. Sed dapibus pulvinar nibh tempor porta.</div></p>

<button class="button" onclick="myFunction()" id="myBtn">Read more</button>


<h2>Research package n°3</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus imperdiet, nulla et dictum interdum, nisi lorem egestas vitae scelerisque enim ligula venenatis dolor.<span id="dots"></span>
<div id="more">
<h3>Related subjects</h3>
{% include list-circles.html items=page.modules %} 

Maecenas nisl est, ultrices nec congue eget, auctor vitae massa. Fusce luctus vestibulum augue ut aliquet. Nunc sagittis dictum nisi, sed ullamcorper ipsum dignissim ac. In at libero sed nunc venenatis imperdiet sed ornare turpis. Donec vitae dui eget tellus gravida venenatis. Integer fringilla congue eros non fermentum. Sed dapibus pulvinar nibh tempor porta.</div></p>
<button class="button" onclick="myFunction()" id="myBtn">Read more</button>



<script>
function myFunction() {
  var dots = document.getElementById("dots");
  var moreText = document.getElementById("more");
  var btnText = document.getElementById("myBtn");

  if (dots.style.display === "none") {
    dots.style.display = "inline";
    btnText.innerHTML = "Read more"; 
    moreText.style.display = "none";
  } else {
    dots.style.display = "none";
    btnText.innerHTML = "Read less"; 
    moreText.style.display = "inline";
  }
}
</script>