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

.myBtn {
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


.card {
background-color: #f5f5f5;
}
</style>

### Project


Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque malesuada mi ac nibh fermentum, ut commodo ligula lacinia. Morbi faucibus, dui sit amet laoreet ultrices, lectus eros pretium augue, in consectetur massa lectus eu lectus. Suspendisse scelerisque sagittis arcu eget facilisis. Aenean ornare cursus urna nec ultrices. Donec quis ornare felis. Morbi viverra vitae ligula quis lacinia. Pellentesque tempor porta eleifend. Ut at nisl eget ligula tempus aliquet vitae vitae magna. Nulla eget neque pellentesque, gravida sapien sit amet, pellentesque magna. Ut orci erat, posuere et elit id, hendrerit interdum ex. Sed varius aliquet justo, vel tempus sapien tristique sit amet.

Phasellus mollis eros lectus, nec vestibulum massa faucibus vel. Duis auctor ex est. Nulla nec egestas orci, commodo semper nisl. Fusce nec odio viverra, malesuada tortor in, varius lectus. Proin eget purus pretium, vulputate turpis sit amet, dignissim nulla. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Sed tincidunt diam eget diam eleifend, vel egestas felis laoreet. Phasellus sed vulputate eros, quis consectetur tellus. Phasellus blandit libero ullamcorper lorem scelerisque blandit. Sed vel diam eleifend, placerat lorem ac, sollicitudin nunc.

Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Morbi sed tortor mollis, faucibus ligula ut, maximus odio. Duis tortor libero, scelerisque in mauris ut, pulvinar hendrerit sapien. Mauris luctus augue et enim gravida, ac vulputate arcu placerat. Nulla facilisi. Cras arcu erat, tempus id tortor sed, viverra viverra neque. Sed aliquam leo mollis ligula auctor, at maximus nisi posuere. Curabitur sed pharetra quam. Nullam egestas neque ipsum, eget aliquet ex congue nec. Morbi turpis nisl, accumsan et nisi et, consequat ullamcorper lectus. 





<div id="package1" class="card" data-package="packageOne">
	<h2>Research package n°1</h2>

	<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus imperdiet, nulla et dictum interdum, nisi lorem egestas vitae scelerisque enim ligula venenatis dolor.<span class="dots"></span>
	<div class="more" style="display: none;">
		<h3>Related subjects</h3>
		{% include list-circles.html items=page.modules %} 

		<p>Maecenas nisl est, ultrices nec congue eget, auctor vitae massa. Fusce luctus vestibulum augue ut aliquet. Nunc sagittis dictum nisi, sed ullamcorper ipsum dignissim ac. In at libero sed nunc venenatis imperdiet sed ornare turpis. Donec vitae dui eget tellus gravida venenatis. Integer fringilla congue eros non fermentum. Sed dapibus pulvinar nibh tempor porta.</p>

		<h3>Latest news of the research package</h3>
		{% include post_displayer.html %}
	
		<h3>Papers</h3>
	
	</div>
	<button  onclick="readMore('packageOne')" class="myBtn">Read more</button>  

</div>





<div id="package2" class="card" data-package="packageTwo">
	<h2>Research package n°2</h2>

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus imperdiet, nulla et dictum interdum, nisi lorem egestas vitae scelerisque enim ligula venenatis dolor.<span class="dots"></span>
<div class="more" style="display: none;">
	<h3>Related subjects</h3>
	{% include list-circles.html items=page.modules %} 

Maecenas nisl est, ultrices nec congue eget, auctor vitae massa. Fusce luctus vestibulum augue ut aliquet. Nunc sagittis dictum nisi, sed ullamcorper ipsum dignissim ac. In at libero sed nunc venenatis imperdiet sed ornare turpis. Donec vitae dui eget tellus gravida venenatis. Integer fringilla congue eros non fermentum. Sed dapibus pulvinar nibh tempor porta.</div></p>

	<button  onclick="readMore('packageTwo')"  class="myBtn">Read more</button>  

</div>



<div id="package3" class="card" data-package="packageThree">
	<h2>Research package n°3</h2>

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus imperdiet, nulla et dictum interdum, nisi lorem egestas vitae scelerisque enim ligula venenatis dolor.<span class="dots"></span>
<div class="more" style="display: none;">
	<h3>Related subjects</h3>
	{% include list-circles.html items=page.modules %} 

Maecenas nisl est, ultrices nec congue eget, auctor vitae massa. Fusce luctus vestibulum augue ut aliquet. Nunc sagittis dictum nisi, sed ullamcorper ipsum dignissim ac. In at libero sed nunc venenatis imperdiet sed ornare turpis. Donec vitae dui eget tellus gravida venenatis. Integer fringilla congue eros non fermentum. Sed dapibus pulvinar nibh tempor porta.</div></p>

	<button  onclick="readMore('packageThree')"  class="myBtn">Read more</button>  

</div>


<script>
function readMore(package) {
    let dots = document.querySelector(`.card[data-package="${package}"] .dots`);
    let moreText = document.querySelector(`.card[data-package="${package}"] .more`); 
    let btnText = document.querySelector(`.card[data-package="${package}"] .myBtn`);

    if (dots.style.display === "none") {
        dots.style.display = "inline-block";
        btnText.textContent = "Read more";
        moreText.style.display = "none";
    } else {
        dots.style.display = "none";
        btnText.textContent = "Read less"; 
        moreText.style.display = "inline-block";
    }
}
</script>