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
    img: /assets/img/avatar-icon.png
  - name: Health
    desc: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sed sapien dignissim, consectetur tellus ultrices, ultricies orci.
    url: https://gohu00.github.io/gemmes_vn/health/
    img: /assets/img/avatar-icon.png
  - name: Migration
    desc: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sed sapien dignissim, consectetur tellus ultrices, ultricies orci.
    url: https://gohu00.github.io/gemmes_vn/migration/
    img: /assets/img/avatar-icon.png

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

<h2>Read More Read Less Button</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus imperdiet, nulla et dictum interdum, nisi lorem egestas vitae scel<span id="dots">...</span><div id="more">erisque enim ligula venenatis dolor.{% include list-circles.html items=page.modules %} Maecenas nisl est, ultrices nec congue eget, auctor vitae massa. Fusce luctus vestibulum augue ut aliquet. Nunc sagittis dictum nisi, sed ullamcorper ipsum dignissim ac. In at libero sed nunc venenatis imperdiet sed ornare turpis. Donec vitae dui eget tellus gravida venenatis. Integer fringilla congue eros non fermentum. Sed dapibus pulvinar nibh tempor porta.</div></p>
<button class="button2" onclick="myFunction()" id="myBtn">Read more</button>









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