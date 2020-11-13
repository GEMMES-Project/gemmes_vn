---
layout: page


---

<style>



body {
  font-family: 'Lora', 'Times New Roman', serif;
  font-weight: bold;
  font-size: 12px;
  line-height: 30px;
  color: #250e62;
  background: #edede9;
  text-align: center;
}

.container {
  max-width: 400px;
  width: 100%;
  margin: 0 auto;
  position: relative;
}

#contact input[type="text"],
#contact input[type="text"],
#contact input[type="text"],
#contact input[type="email"],
#contact button[type="submit"] {
  font: 400 12px/16px "Roboto", Helvetica, Arial, sans-serif;
}

#contact {
  background: #F9F9F9;
  padding: 25px;
  margin: 150px 0;
  box-shadow: 0 0 20px 0 rgba(0, 0, 0, 0.2), 0 5px 5px 0 rgba(0, 0, 0, 0.24);
}

#contact h3 {
  display: block;
  font-size: 30px;
  font-weight: 300;
  margin-bottom: 10px;
  font-weight: bold;
}

#contact h4 {
  margin: 5px 0 15px;
  display: block;
  font-size: 13px;
  font-weight: 400;
  font-weight: bold;
}

fieldset {
  border: medium none !important;
  margin: 0 0 10px;
  min-width: 100%;
  padding: 0;
  width: 100%;
}

#contact input[type="text"],
#contact input[type="text"],
#contact input[type="text"],
#contact input[type="email"]{
  width: 100%;
  border: 1px solid #ccc;
  background: #FFF;
  margin: 0 0 5px;
  padding: 10px;
}

#contact input[type="text"]:hover,
#contact input[type="text"]:hover,
#contact input[type="text"]:hover,
#contact input[type="email"]:hover{
  -webkit-transition: border-color 0.3s ease-in-out;
  -moz-transition: border-color 0.3s ease-in-out;
  transition: border-color 0.3s ease-in-out;
  border: 1px solid #aaa;
}


#contact button[type="submit"] {
  cursor: pointer;
  width: 100%;
  border: none;
  background: #250e62;
  color: #FFF;
  margin: 0 0 5px;
  padding: 10px;
  font-size: 15px;
}

#contact button[type="submit"]:hover {
  background: #da291c;
  -webkit-transition: background 0.3s ease-in-out;
  -moz-transition: background 0.3s ease-in-out;
  transition: background-color 0.3s ease-in-out;
}

#contact button[type="submit"]:active {
  box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.5);
}

.copyright {
  text-align: center;
}

#contact input:focus,
#contact textarea:focus {
  outline: 0;
  border: 1px solid #aaa;
}

::-webkit-input-placeholder {
  color: #888;
}

:-moz-placeholder {
  color: #888;
}

::-moz-placeholder {
  color: #888;
}

:-ms-input-placeholder {
  color: #888;
}




</style>



<div class="container" >
<form name="contact" id="contact" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSelzhlAQN_RwGjoX9ltfYq37SMemGmJt6hyr4_-3RAllsd5KQ/formResponse?" target="hidden_iframe" onsubmit="submitted=true;">
    <h3>Register for the webinar</h3>
    <h4>Please fill in the following form.</h4>
    <fieldset>
      <input name="entry.1361743724" id="entry.1361743724" placeholder="First name" type="text" tabindex="1" required autofocus>
    </fieldset>
	<fieldset>
      <input name="entry.906964234" id="entry.906964234" placeholder="Last name" type="text" tabindex="2" required>
    </fieldset>
	<fieldset>
      <input name="entry.XXXXXX" id="entry.XXXXXXXX" placeholder="Institution" type="test" tabindex="3" required>
    </fieldset>
    <fieldset>
      <input name="entry.1500516366" id="entry.1500516366" placeholder="Your Email Address" type="email" tabindex="4" required>
    </fieldset>
        <fieldset>
      <button name="submit" type="submit" id="contact-submit" data-submit="...Sending">Submit</button>
    </fieldset>
</form>
</div>
<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>



<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
$('#contact').on('submit', function(e) {
  $('#contact *').fadeOut(2000);
  $('#contact').prepend('Your submission has been processed. Thank you! An invitation will be sent to you by email a few days before the webinar.');
  });
</script>