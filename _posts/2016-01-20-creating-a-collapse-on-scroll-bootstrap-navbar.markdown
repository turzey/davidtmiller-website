---
layout:     post
title:      "Creating a Collapse-On-Scroll Bootstrap Navbar"
subtitle:   "Using the Built In Bootstrap Affix Plugin"
date:       2016-01-20 13:00:00
author:     "David Miller"
header-img: "img/post-bg-01.jpg"
---

<div class="row">

	<div class="col-lg-8 col-lg-offset-2 col-md-10 col-md-offset-1">

		<p>Collapsing navigation bars are a very popular design choice, and can add a nice dynamic touch to many types of websites. There are loads of plugins and code snippets out there to help you achieve the effect, but what makes this method unique is that it uses built-in Bootstrap components to create the animated collapse-on-scroll effect rather than using additional third party plugins. This means you wont have to import any extra JavaScript libraries into your project or add any other additional resources other than your core Bootstrap files and jQuery.</p>

		<p>In this short, beginner level code review, we won't be using anything more than the default Bootstrap navbar, a bit of jQuery to activate the Bootstrap Affix plugin, and a little bit of custom CSS. For the more advanced designers out there, feel free to use your CSS pre-processor of choice or any other tools, but for the purposes of this guide I wanted to keep things as simple as possible!</p>

		<p>That being said, here is the collapse-on-scroll Bootstrap navbar that we will be exploring in this post:</p>

	</div>

	<div class="col-lg-12">

		<p data-height="540" data-theme-id="0" data-slug-hash="yepJoX" data-default-tab="result" data-user="davidtmiller" class='codepen'>See the Pen <a href='http://codepen.io/davidtmiller/pen/yepJoX/'>Easy Bootstrap Collapsing Animated Navigation on Scroll</a> by David Miller (<a href='http://codepen.io/davidtmiller'>@davidtmiller</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
		<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

	</div>

	<div class="col-lg-8 col-lg-offset-2 col-md-10 col-md-offset-1">

		<h2 class="section-heading">HTML Markup</h2>

		<p>First we'll take a look at the HTML markup for this menu customization. It's not that far from the default Bootstrap menu.</p>
		<pre>
<nav id="mainNav" class="navbar navbar-default navbar-fixed-top">
  <div class="container">
    <!-- Brand and toggle get grouped for better mobile display -->
    <div class="navbar-header">
      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="#">Start Bootstrap</a>
    </div>

    <!-- Collect the nav links, forms, and other content for toggling -->
    <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
      <ul class="nav navbar-nav navbar-right">
        <li>
          <a href="#">About</a>
        </li>
        <li>
          <a href="#">Services</a>
        </li>
        <li>
          <a href="#">Portfolio</a>
        </li>
        <li>
          <a href="#">Contact</a>
        </li>
      </ul>
    </div>
    <!-- /.navbar-collapse -->
  </div>
  <!-- /.container -->
</nav>

<!-- Demo Header -->
<header>
  <h1>Bootstrap Collapsing Animated Navigation</h1>
</header>
		</pre>

	</div>

</div>