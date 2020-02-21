---
layout: page
title: Resume
permalink: /resume/
image: 
---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
.accordion {
  background-color: #000060;
  color: #ffffff;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
  transition: 0.4s;
}

.active, .accordion:hover {
  background-color: #000080;
}

.accordion:after {
  content: '\002B';
  color: #777;
  font-weight: bold;
  float: right;
  margin-left: 5px;
}

.active:after {
  content: "\2212";
}

.panel {
  padding: 0 18px;
  background-color: white;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
}
</style>
</head>
<body>

<h2>Pritam</h2>
<h3>Content Writer & Editor</h3>
<table style="width:100%">
  <tr>
    <td width="50%"> <p><i class="fa fa-envelope" style="color:#000060;"></i> hello@pritam.io</p></td>
    <td width="50%"> <p><i class="fa fa-phone" style="color:#000060;"></i> +91 7829171196</p></td>
  </tr>
  <tr>
    <td width="50%"> <p><i class="fa fa-desktop" style="color:#000060;"></i> <a href="https://pritam.io" target="_blank">pritam.io</a>
</p></td>
    <td width="50%"> <p><i class="fa fa-linkedin-square" style="color:#000060;"></i> <a href="https://www.linkedin.com/in/pritamtheargumentativeyouth/" target="_blank">pritamtheargumentativeyouth</a></p></td>
  </tr>
  <tr>
    <td width="50%"> <p><i class="fa fa-twitter" style="color:#000060;"></i> <a href="https://twitter.com/prritam" target="_blank">@prritam</a></p></td>
    <td width="50%"> <p><i class="fa fa-medium" style="color:#000060;"></i> <a href="https://medium.com/@prritam" target="_blank">@prritam</a></p></td>
  </tr> 
  <tr>
    <td width="50%"> <p><i class="fa fa-facebook" style="color:#000060;"></i> <a href="https://www.facebook.com/prritam" target="_blank">prritam</a></p></td>
    <td width="50%"> <p><i class="fa fa-instagram" style="color:#000060;"></i> <a href="https://www.instagram.com/murphyable/" target="_blank">murphyable</a></p></td>
  </tr>
</table>

<p>In this example we have added a "plus" sign to each button. When the user clicks on the button, the "plus" sign is replaced with a "minus" sign.</p>
<h3>Work Experience</h3>
<button class="accordion">Section 1</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<p>Huhahahahaha</p>

<button class="accordion">Section 2</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<button class="accordion">Education</button>
<div class="panel">
  <h3>MS Communication</h3>
  <p><strong>St. Joseph's College (Autonomous), Bangalore - 2015-2017</strong></p>
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
  <h3>BE Electronics & Communication</h3>
  <p><strong>Acharya Institute of Technology, Bangalore - 2008-2013</strong></p>
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var panel = this.nextElementSibling;
    if (panel.style.maxHeight) {
      panel.style.maxHeight = null;
    } else {
      panel.style.maxHeight = panel.scrollHeight + "px";
    } 
  });
}
</script>

</body>
</html>
