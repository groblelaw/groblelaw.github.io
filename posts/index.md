---
layout: post-list
title: Contact Us
excerpt: "A List of Posts"
comments: false
---

<form method="post" action="https://formspree.io/wgroble@tulane.edu" method="POST">
	<div class="field half first">
		<label for="name">Name</label>
		<input type="text" name="name" id="name" />
	</div>
	<div class="field half">
		<label for="email">Email</label>
		<input type="text" name="_replyto" id="email" />
	</div>
	<div class="field">
		<label for="message">Message</label>
		<textarea name="message" id="message" rows="5"></textarea>
	</div>
	<ul class="actions">
		<input type="submit" value="Send Message">
		<input type="hidden" name="_next" value="#" />
		<!--<li><a href="" class="button submit">Send Message</a></li>-->
	</ul>
</form>