---
layout: page-fullwidth
header: no
title: Connect and Contribute
#image:
#   file: <image filename in images folder>
#   title: <text describing the image>
---

<div class="small-4 columns">

<h1 id="contribute">Contribute</h1>

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=LK8R7BR5HAHMS&source=url">Donate to the campaign through PayPal</a>

<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick" />
<input type="hidden" name="hosted_button_id" value="LK8R7BR5HAHMS" />
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
<img alt="PayPal" border="0" src="https://www.paypal.com/en_US/i/scr/pixel.gif" width="1" height="1" />
</form>

<br>
<br>

<h1 id="contact">Contact Information</h1>

Andrew B. Felder
<br>
andrewbfelder@gmail.com
<br>
(734) 344-2579

<p>
<ul class="inline-list social-icons">
{% for social_item in site.data.socialmedia %}
  <li><a href="{{ social_item.url }}" target="_blank" class="{{ social_item.class }}" title="{{ social_item.title }}"></a></li>
{% endfor %}
</ul>
</p>

</div>


<div class="small-8 columns">

<h1 id="involved" style="margin-left: 40px;">Get Involved</h1>

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdUGbMT6vqbKZqR-b4GqN5LzPjtQW0CzVXnVCuYKBt4Z5Ah6g/viewform?embedded=true" width="640" height="1100" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>

</div>

