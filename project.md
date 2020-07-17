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

	<i>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus imperdiet, nulla et dictum interdum, nisi lorem egestas vitae scelerisque enim ligula venenatis dolor.</i><span class="dots"></span>
	<div class="more" style="display: none;">
	<img src="https://gohu00.github.io/gemmes_vn/assets/img/path.jpg">


		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin in facilisis mauris, vel aliquam tellus. Vestibulum tincidunt iaculis rhoncus. Cras nibh leo, ultricies id enim id, viverra sagittis ipsum. Vestibulum facilisis elit felis. Praesent purus nisi, euismod eu commodo quis, venenatis in arcu. Mauris dictum nisi nisi, quis efficitur libero egestas nec. Nullam non eros ut metus lacinia viverra et in nisl. Sed eros magna, blandit nec ultricies sit amet, sollicitudin auctor ex. </p>
		<p>Mauris dictum nisi odio, id suscipit leo dignissim ut. In dapibus eu orci et mollis. Curabitur eget dui et sem euismod pellentesque. Donec semper rutrum nulla, eget fermentum ex fermentum quis. Nam sodales, tellus sed pellentesque dictum, orci dui tristique nisi, eu posuere felis dui a enim. Ut a vulputate quam. Cras consequat elit a nunc pretium lacinia. Aliquam malesuada, quam quis tristique porta, ante ligula luctus odio, id semper erat augue vitae velit. In euismod sagittis lacus in viverra. Etiam placerat auctor odio vitae malesuada. Vestibulum eleifend diam at urna iaculis congue. Maecenas ac ipsum non tortor lacinia dictum nec nec magna. Curabitur nunc magna, euismod non odio eu, consectetur aliquet mauris. </p>
		<p>Nulla rhoncus rhoncus eros, eu dignissim tortor feugiat vel. Nam elementum pellentesque lectus nec ultrices. Integer semper hendrerit neque, sit amet elementum mi laoreet at. Mauris eleifend felis volutpat placerat efficitur. Nunc congue, dui eu rhoncus euismod, neque massa aliquet nulla, non scelerisque lorem enim sit amet urna. Sed lobortis tincidunt enim vitae pharetra. Sed nec convallis sapien. Nulla erat mauris, gravida a porttitor ac, cursus nec elit.  </p>		
		
		<h3>Related subjects</h3>
		{% include list-circles.html items=page.modules %} 
		
		<h3>Latest news of the research package</h3>
		{% include post_displayer_packageOne.html %}
	
		<h3>Papers</h3>
		<i>coming soon</i>
	</div>
	<button  onclick="readMore('packageOne')" class="myBtn">Read more</button>  





<div id="package2" class="card" data-package="packageTwo">
	<h2>Research package n°2</h2>

	<i>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus imperdiet, nulla et dictum interdum, nisi lorem egestas vitae scelerisque enim ligula venenatis dolor.</i><span class="dots"></span>
	<div class="more" style="display: none;">
	<img src="https://gohu00.github.io/gemmes_vn/assets/img/path.jpg">
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin in facilisis mauris, vel aliquam tellus. Vestibulum tincidunt iaculis rhoncus. Cras nibh leo, ultricies id enim id, viverra sagittis ipsum. Vestibulum facilisis elit felis. Praesent purus nisi, euismod eu commodo quis, venenatis in arcu. Mauris dictum nisi nisi, quis efficitur libero egestas nec. Nullam non eros ut metus lacinia viverra et in nisl. Sed eros magna, blandit nec ultricies sit amet, sollicitudin auctor ex. </p>
		<p>Mauris dictum nisi odio, id suscipit leo dignissim ut. In dapibus eu orci et mollis. Curabitur eget dui et sem euismod pellentesque. Donec semper rutrum nulla, eget fermentum ex fermentum quis. Nam sodales, tellus sed pellentesque dictum, orci dui tristique nisi, eu posuere felis dui a enim. Ut a vulputate quam. Cras consequat elit a nunc pretium lacinia. Aliquam malesuada, quam quis tristique porta, ante ligula luctus odio, id semper erat augue vitae velit. In euismod sagittis lacus in viverra. Etiam placerat auctor odio vitae malesuada. Vestibulum eleifend diam at urna iaculis congue. Maecenas ac ipsum non tortor lacinia dictum nec nec magna. Curabitur nunc magna, euismod non odio eu, consectetur aliquet mauris. </p>
		<p>Nulla rhoncus rhoncus eros, eu dignissim tortor feugiat vel. Nam elementum pellentesque lectus nec ultrices. Integer semper hendrerit neque, sit amet elementum mi laoreet at. Mauris eleifend felis volutpat placerat efficitur. Nunc congue, dui eu rhoncus euismod, neque massa aliquet nulla, non scelerisque lorem enim sit amet urna. Sed lobortis tincidunt enim vitae pharetra. Sed nec convallis sapien. Nulla erat mauris, gravida a porttitor ac, cursus nec elit.  </p>		

		
		<h3>Related subjects</h3>
		{% include list-circles.html items=page.modules %} 


		<h3>Latest news of the research package</h3>
		{% include post_displayer_packageTwo.html %}
	
		<h3>Papers</h3>
		<i>coming soon</i>
	</div>	
	<button  onclick="readMore('packageTwo')"  class="myBtn">Read more</button>  





<div id="package3" class="card" data-package="packageThree">
	<h2>Research package n°3</h2>

	<i>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus imperdiet, nulla et dictum interdum, nisi lorem egestas vitae scelerisque enim ligula venenatis dolor.</i><span class="dots"></span>
	<div class="more" style="display: none;">
	<img src="https://gohu00.github.io/gemmes_vn/assets/img/path.jpg">
		
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin in facilisis mauris, vel aliquam tellus. Vestibulum tincidunt iaculis rhoncus. Cras nibh leo, ultricies id enim id, viverra sagittis ipsum. Vestibulum facilisis elit felis. Praesent purus nisi, euismod eu commodo quis, venenatis in arcu. Mauris dictum nisi nisi, quis efficitur libero egestas nec. Nullam non eros ut metus lacinia viverra et in nisl. Sed eros magna, blandit nec ultricies sit amet, sollicitudin auctor ex. </p>
		<p>Mauris dictum nisi odio, id suscipit leo dignissim ut. In dapibus eu orci et mollis. Curabitur eget dui et sem euismod pellentesque. Donec semper rutrum nulla, eget fermentum ex fermentum quis. Nam sodales, tellus sed pellentesque dictum, orci dui tristique nisi, eu posuere felis dui a enim. Ut a vulputate quam. Cras consequat elit a nunc pretium lacinia. Aliquam malesuada, quam quis tristique porta, ante ligula luctus odio, id semper erat augue vitae velit. In euismod sagittis lacus in viverra. Etiam placerat auctor odio vitae malesuada. Vestibulum eleifend diam at urna iaculis congue. Maecenas ac ipsum non tortor lacinia dictum nec nec magna. Curabitur nunc magna, euismod non odio eu, consectetur aliquet mauris. </p>
		<p>Nulla rhoncus rhoncus eros, eu dignissim tortor feugiat vel. Nam elementum pellentesque lectus nec ultrices. Integer semper hendrerit neque, sit amet elementum mi laoreet at. Mauris eleifend felis volutpat placerat efficitur. Nunc congue, dui eu rhoncus euismod, neque massa aliquet nulla, non scelerisque lorem enim sit amet urna. Sed lobortis tincidunt enim vitae pharetra. Sed nec convallis sapien. Nulla erat mauris, gravida a porttitor ac, cursus nec elit.  </p>		

		
		<h3>Related subjects</h3>
		{% include list-circles.html items=page.modules %} 


		<h3>Latest news of the research package</h3>
		{% include post_displayer_packageOne.html %}
	
		<h3>Papers</h3>
		<i>coming soon</i>
	</div>
	<button  onclick="readMore('packageThree')"  class="myBtn">Read more</button>  




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