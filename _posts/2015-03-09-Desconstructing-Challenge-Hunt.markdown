---
layout: post
title: Deconstructing Challenge Hunt
category: Coding
tags: chrome-extension
year: 2015
month: 3
day: 09
published: true
summary: Two weeks of hacking and hustling to finally launch Challenge Hunt.
image: challengehunt.png
---

<div class="row">
	<div class="span8 columns">
	  <blockquote>
	  	<p>Hey! Were you able to solve that problem in the long contest?</p>
	  </blockquote>
	  <p>If you belong to the coding community, you'll know what I'm talking about. This is the common lingo. I have been a developer for a over a year now but I was new to this type of programming. So, just like everyone else from the community I decided to participate in online programming challenges to sharpen my problem solving skills. <a href="http://codechef.com/" target="_blank">CodeChef</a> was the most popular and the only choice among my peer group so that seemed that obvious choice for me to begin. Soon, I realised that apart from <a href="http://codechef.com/" target="_blank">CodeChef</a> there were numerous other online challenge platforms like <a href="https://www.hackerrank.com/" target="_blank">HackerRank</a>, <a href="https://www.hackerearth.com/" target="_blank">HackerEarth</a>, <a href="https://www.topcoder.com/" target="_blank">TopCoder</a> and the likes which offered a variety of programming challenges. After knowing this I felt the need for a place where I could see all the active and upcoming programming challenges from multiple platforms. I asked about this to several of programmer friends and came to know that there was none. Being a product guy I decided to build such a place. When I told my friend <a href="http://gw.linkedin.com/pub/chirrag-nangia/7a/651/721" target="_blank">Chirrag</a> about this, he seemed equally excited. So we decided to hack on it together.</p>
	  <p>This was the basis for Challenge Hunt. Here's how we hacked on it.</p> 

	  <h2>The Initial Idea</h2>
	  <p> The idea was simple: to create a chrome extension (since it has the most desktop users) which showed people all the active and upcoming programming challenges. Initially we thought of scraping the data from 4-5 popular online programming challenge platforms and showing it in the extension UI. But when we came up with this idea, we realised that since the problem was so common someone else might have already solved it. It was then that we stumbled across <a href="http://clist.by" target="_blank">clist.by</a> which had already listed programming challenges from numerous platforms. This made our job much easier and removed what seemed the only hurdle in building Challenge Hunt.

	  <h2>Two weeks of hacking</h2>
	  ---
	  layout: post
	  image: hacking.jpg
	  ---
	  <p>After two weeks of continuous hacking we were finally able to launch <a href="http://bit.ly/1E3T9sP" target="_blank">Challenge Hunt</a>. But this wasn't a one step process. We first prototyped a basic version, showed it to a couple of people and then made changes to it based on the feedback. This happened a few before we started showing some love.
	  <blockquote>
	  	<p>pretty solid idea, I can see this would be so much relevant to a certain class of people. (y)</p>
	  </blockquote>
	  <blockquote>
	  	<p>liked the color selection<br>
		good work (y)</p>
	  </blockquote>
	  <p>This is when we considered launching Challenge Hunt.</p>

	  <h2>Get on the hunt!</h2>
	  <p>We launched Challenge Hunt yesterday i.e. 8 March, 2015 and are already seeing a good response.</p>

	  <p>Get <a href="http://bit.ly/1E3T9sP" target="_blank">Challenge Hunt</a> and get on the hunt!</p> 
	</div>
</div> 

<div class="row">
	<div class="span3 columns">&nbsp;</div>
	<div class="span6 column">
			<p class="pull-right">{% if page.previous.url %} <a href="{{page.previous.url}}" title="Previous Post: {{page.previous.title}}"><i class="icon-chevron-left"></i></a> 	{% endif %}   {% if page.next.url %} 	<a href="{{page.next.url}}" title="Next Post: {{page.next.title}}"><i class="icon-chevron-right"></i></a> 	{% endif %} </p>  
	</div>
</div>
	
<!-- <div class="row">
	<div class="span9 columns">    
		<h2>Comments Section</h2>
	    <p>Feel free to comment on the post but keep it clean and on topic.</p>	
		<div id="disqus_thread"></div>
		<script type="text/javascript">
			/* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
			var disqus_shortname = 'ericjones'; // required: replace example with your forum shortname
			var disqus_identifier = '{{ page.url }}';
			var disqus_url = 'http://erjjones.github.com{{ page.url }}';
			
			/* * * DON'T EDIT BELOW THIS LINE * * */
			(function() {
				var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
				dsq.src = 'http://' + disqus_shortname + '.disqus.com/embed.js';
				(document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
			})();
		</script>
		<noscript>Please enable JavaScript to view the <a href="http://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
		<a href="http://disqus.com" class="dsq-brlink">blog comments powered by <span class="logo-disqus">Disqus</span></a>
	</div>
</div> -->

<!-- Twitter -->
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src="//platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>

<!-- Google + -->
<script type="text/javascript">
  (function() {
    var po = document.createElement('script'); po.type = 'text/javascript'; po.async = true;
    po.src = 'https://apis.google.com/js/plusone.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(po, s);
  })();
</script>
