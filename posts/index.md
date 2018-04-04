---
layout: page
title: Contact Us
excerpt: "Contact Us"
comments: false
---
<div id="contact-container" align="center">
<form method="post" action="https://formspree.io/wgroble@tulane.edu" method="POST">
	<div class="field half first">
		<label for="name">Name</label><br />
		<input type="text" name="name" id="name" style="width: 100%; border-radius: 2px;"/>
	</div>
	<div class="field half">
		<label for="email">Email</label><br />
		<input type="text" name="_replyto" id="email" style="width: 100%; border-radius: 2px;"/>
	</div>
	<div class="field">
		<label for="message">Message</label><br />
		<textarea name="message" id="message" rows="5" style="width: 100%; border-radius: 2px;"></textarea>
	</div>
	<ul class="actions">
	<br />
		<input type="submit" value="Send Message">
		<input type="hidden" name="_next" value="#" />
		<!--<li><a href="" class="button submit">Send Message</a></li>-->
	</ul>
</form>
</div>