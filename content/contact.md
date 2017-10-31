+++
title = "Contact"
weight = 50
date = 2017-10-25T21:45:11-07:00
draft = false
+++
If you would like to book The Dizzys for your next event, please feel free to send us a message. We would love to send you our electronic press kit to tell you a little more about the band.

<small>&ast;required field</small>

<form action="https://formspree.io/thedizzysband@gmail.com" method="POST">
	<div class="field half first">
		<label for="name">Name&ast;</label>
		<input type="text" name="name" id="name" required />
	</div>
	<div class="field half">
		<label for="email">Email&ast;</label>
		<input type="text" name="email" id="email" required />
	</div>
	<div class="field half first">
		<label for="venue">Venue</label>
		<input type="text" name="venue" id="venue" />
	</div>
	<div class="field half">
		<label for="date">Date of Show</label>
		<input type="date" name="date" id="date" />
	</div>
	<div class="field">
		<label for="message">Message&ast;</label>
		<textarea name="message" id="message" rows="4" required></textarea>
	</div>
	<div class="field">
        <label for="epk"><input type="checkbox" name="epk" value="send" id="epk" />Send me the Electronic Press Kit!</label>
	</div>
	<input type="hidden" name="_subject" value="New Contact Form Submission from TheDizzysBand.com" />
	<ul class="actions">
		<li><input type="submit" value="Send Message" class="special" /></li>
		<li><input type="reset" value="Reset" /></li>
	</ul>
</form>

{{< socialLinks >}}