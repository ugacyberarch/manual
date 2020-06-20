---
layout: default
title: Phishing
description: Fake Links

---
# Fake Links

Many phishing attacks deceive their victims with a very simple trick. They show a link that looks legitimate but does not go where you might expect.

> **Does this link go where you expect?**
>
> [**http://paypal.com/account**](https://en.wikipedia.org/wiki/Phishing "http://paypal.com/account")

Websites, and many of the e-mails you receive use a special format called HTML that allows you to add structured and interactive elements.

For example, if you wanted to make a table:

<!-- HTML table Interactive Activity -->
<div class="html-table" data-v-99ac6492><div class="header" data-v-99ac6492><div class="left" data-v-99ac6492><h4 data-v-99ac6492>HTML:</h4><span data-v-99ac6492>What your computer receives.</span></div><div class="right" data-v-99ac6492><h4 data-v-99ac6492>Webpage:</h4><span data-v-99ac6492>What you see.</span></div></div><div class="left" data-v-99ac6492><textarea wrap="off" data-v-99ac6492>&lt;table&gt;
  &lt;tr&gt;
    &lt;td&gt;Book&lt;/td&gt;
    &lt;td&gt;Price&lt;/td&gt;
  &lt;/tr&gt;
  &lt;tr&gt;
    &lt;td&gt;Charlotte's Web&lt;/td&gt;
    &lt;td&gt;$2.99&lt;/td&gt;
  &lt;/tr&gt;
  &lt;tr&gt;
    &lt;td&gt;Where The Wild Things Are&lt;/td&gt;
    &lt;td&gt;$5.98&lt;/td&gt;
  &lt;/tr&gt;
&lt;/table&gt;</textarea></div><div class="right" data-v-99ac6492><div class="content" data-v-99ac6492><table>
  <tr>
    <td>Book</td>
    <td>Price</td>
  </tr>
  <tr>
    <td>Charlotte's Web</td>
    <td>$2.99</td>
  </tr>
  <tr>
    <td>Where The Wild Things Are</td>
    <td>$5.98</td>
  </tr>
</table></div></div></div>
<!-- HTML table Interactive Activity -->


Those odd things wrapping the real content, like `<table>` and `<tr>`, are called "tags". You may have deduced that `<table>` indicates the beginning of our table and `</table>`, with the extra slash, marks the end. Likewise with the table rows and table data.

HTML is just a standard we started using, nothing magical, it is as arbitrary as which side of the road we drive on and similarly unlikely to change anytime soon.

It is important to remember that there is a disconnect between what your computer receives and what it shows you; especially when it comes to the links you see and click.

**So, how do HTML links work?**

Links in HTML are created with `<a> </a>` tags, but they also have an additional `href` attribute that says where the link takes you.

That is the most important part. What a link says, and where a link goes is not always the same.

## The `<a>` Team

Try it for yourself. You can make your own link that goes anywhere you want and says anything you want.

<!-- href Interactive Activity -->
<div class="phishing-link" data-v-514aecbe><div class="row" data-v-514aecbe><span data-v-514aecbe>&lt;a href=&quot;</span><input title="Where you go." data-tippy data-tippy-arrow="true" data-tippy-placement="right" data-tippy-trigger="manual" data-tippy-hideonclick="persistent" data-tippy-distance="30" data-tippy-flip="false" value="https://en.wikipedia.org/wiki/Phishing" class="href" data-v-514aecbe><span data-v-514aecbe>&quot;&gt;</span><br data-v-514aecbe><input title="What you see." data-tippy data-tippy-arrow="true" data-tippy-placement="right" data-tippy-trigger="manual" data-tippy-hideonclick="persistent" data-tippy-flip="false" value="http://paypal.com/account" class="content" data-v-514aecbe><br data-v-514aecbe><span data-v-514aecbe>&lt;/a&gt;</span></div><div class="row" data-v-514aecbe><a href="https://en.wikipedia.org/wiki/Phishing" data-v-514aecbe>http://paypal.com/account</a></div></div>
<!-- href Interactive Activity -->


## Hovering

Savvy users know that by pointing to a link, but not clicking it, you may get a clue to where it will take you. Try hovering over the `Click HERE!` link below.

<!-- hover link Interactive Activity -->
<div class="browser-window" data-v-3262b446><div class="row" data-v-3262b446><div class="column left" data-v-3262b446><span class="dot" style="background:#ed594a;" data-v-3262b446></span><span class="dot" style="background:#fdd800;" data-v-3262b446></span><span class="dot" style="background:#5ac05a;" data-v-3262b446></span><div class="nav" data-v-3262b446><i class="back fas fa-arrow-left" data-v-3262b446></i><i class="forward fas fa-arrow-right" data-v-3262b446></i><i class="forward fas fa-redo" data-v-3262b446></i></div></div><div class="column middle" data-v-3262b446><input type="text" disabled="disabled" value="http://example.com" data-v-3262b446></div><div class="column right" data-v-3262b446><div style="float:right" data-v-3262b446><span class="bar" data-v-3262b446></span><span class="bar" data-v-3262b446></span><span class="bar" data-v-3262b446></span></div></div></div><div class="content" data-v-3262b446><div class="hover-link" data-v-eedd5baa><div class="link" data-v-eedd5baa><a href="http://example.com/test" data-v-eedd5baa>
      Click HERE!
    </a></div><!----><!----></div></div></div>
<!-- hover link Interactive Activity -->


Check the bottom of your own browser window when you hover over a link, it may show something similar.

It is an excellent idea to "look before you leap", but unfortunately even the status bar is not completely trustworthy. Try clicking the link, it won't take you where it says!

Why did we even bring it up? Well, we don't want you to have a false sense of security. There is really one authority for where you are and where you end up, and that is the **address bar**:

## URLs

Clicking a link makes your browser go to another address. Addresses can also be copied or typed directly into the address bar.

The address bar is pretty flexible, but it does require some understanding of a web standard called URLs (Uniform Resource Locators) to use.

Wait, "links", "addresses", "URLs"?

Links are what we actually click on; they take us to an address, which is also called a URL. Don't worry about it, you can call them "links", "addresses", or "URLs".

The important part is you understand how to read the address bar to determine if you are where you expect to be. So, let's decipher a URL.

## Searching

The way we use the internet has been completely changed by "search engines". A lot of people navigate the internet by searching for every website they use.

In fact, browsers have acknowledged this trend and have integrated search into the address bar. Perhaps you remember just a few years ago when browsers had two separate fields, and we used the field on the right side to search.

Now that you know how the address bar works, instead of searching, you might try to type out important domain names instead of searching for them.

For example, instead of searching for `PayPal`, go ahead and add `.com` so you go directly there.

Malware and malicious plugins have been known to show fake search results so that you mistakenly go to a bad website.

## Address Bar

Imagine for a second that your bank is on the 4th floor of a building. You will likely use the elevator to reach your bank. So, you get into the elevator and you press the button. The doors close, the elevator takes you up, and the doors open.

How do you know that you are actually on the floor you want to be on?

In many ways, links on webpages and in your e-mail are like the buttons inside an elevator. You click the link and you expect it to take you to the right place.

You might also look for confirmation that you are where you want to be — perhaps a placard that shows the floor you are on, maybe there is an indicator above the doors, or maybe you will just look out and see if it looks like your bank.


<!-- Elevator Interactive Activity -->
<div class="browser-window" data-v-3262b446><div class="row" data-v-3262b446><div class="column left" data-v-3262b446><span class="dot" style="background:#ed594a;" data-v-3262b446></span><span class="dot" style="background:#fdd800;" data-v-3262b446></span><span class="dot" style="background:#5ac05a;" data-v-3262b446></span><div class="nav" data-v-3262b446><i class="back fas fa-arrow-left" data-v-3262b446></i><i class="forward fas fa-arrow-right" data-v-3262b446></i><i class="forward fas fa-redo" data-v-3262b446></i></div></div><div class="column middle" data-v-3262b446><input type="text" disabled="disabled" value="http://office-building.com/ground-floor" data-v-3262b446></div><div class="column right" data-v-3262b446><div style="float:right" data-v-3262b446><span class="bar" data-v-3262b446></span><span class="bar" data-v-3262b446></span><span class="bar" data-v-3262b446></span></div></div></div><div class="content" data-v-3262b446><div class="elevator" data-v-04dc064e><svg width="640" height="480" xmlns="http://www.w3.org/2000/svg" data-v-04dc064e><defs data-v-04dc064e><linearGradient id="b" spreadMethod="reflect" x1=".452" x2=".445" y1=".438" y2=".973" data-v-04dc064e><stop offset="0" stop-color="#999" data-v-04dc064e></stop><stop offset="1" stop-color="#666" data-v-04dc064e></stop><stop offset="1" stop-color="#666" data-v-04dc064e></stop></linearGradient><linearGradient id="a" spreadMethod="reflect" x1=".511" x2="1" y2="1" data-v-04dc064e><stop offset="0" stop-color="#999" data-v-04dc064e></stop><stop offset="1" stop-color="#666" data-v-04dc064e></stop><stop offset="1" stop-color="#666" data-v-04dc064e></stop></linearGradient><clipPath id="doorframe" data-v-04dc064e><path d="m135.210114,83.445358l345.378174,0l0,350.420166l-345.378174,0l0,-350.420166z" data-v-04dc064e></path></clipPath></defs><svg width="40" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 490.667 490.667" style="display: none;" data-v-04dc064e><path d="M405.333 149.333c-17.673 0-32 14.327-32 32V160c0-17.673-14.327-32-32-32-17.673 0-32 14.327-32 32v-21.333c0-17.673-14.327-32-32-32-17.673 0-32 14.327-32 32V32c0-17.673-14.327-32-32-32s-32 14.327-32 32v266.667l-74.069-37.035A53.341 53.341 0 0 0 83.413 256c-16.613 0-30.08 13.467-30.08 30.08v.128a30.077 30.077 0 0 0 8.811 21.333l137.941 137.941a154.454 154.454 0 0 0 109.248 45.184c70.692 0 128-57.308 128-128V181.333c0-17.673-14.326-32-32-32z" fill="#ffcc80" data-v-04dc064e></path><g fill="#ffb74d" data-v-04dc064e><path d="M256 114.987v119.68c0 5.891-4.776 10.667-10.667 10.667V138.667A31.297 31.297 0 0 1 256 114.987zM320 136.32v98.347c0 5.891-4.776 10.667-10.667 10.667V160A31.298 31.298 0 0 1 320 136.32zM384 157.653v77.013c0 5.891-4.776 10.667-10.667 10.667v-64A31.3 31.3 0 0 1 384 157.653z" data-v-04dc064e></path></g></svg><g class="layer" data-v-04dc064e><g style="clip-path: url(#doorframe);" data-v-04dc064e><path fill="url(#b)" fill-opacity=".75" stroke="#666" stroke-width="2" d="M312.93 75.74h177v358.397h-177z" class="door right" data-v-04dc064e></path><path fill="url(#b)" fill-opacity=".75" stroke="#666" stroke-width="2" d="M135.195 75.776h177v358.397h-177z" class="door left" data-v-04dc064e></path></g><g fill-opacity=".31" data-v-04dc064e><ellipse cx="524.189" cy="196.826" fill="url(#a)" rx="5.714" ry="5.714" data-v-04dc064e></ellipse><text font-family="Monospace" font-size="7" stroke="#666" stroke-dasharray="null" stroke-linecap="null" stroke-linejoin="null" stroke-width="0" text-anchor="middle" x="524.052" y="199.315" data-v-04dc064e>
          10
        </text></g><path fill="url(#a)" fill-opacity=".31" d="M511.267 137.35h52.571v95.446h-52.571z" data-v-04dc064e></path><path fill="#666" d="M117.5 76.5h18v362h-18z" data-v-04dc064e></path><g fill-opacity=".31" data-v-04dc064e><ellipse cx="523.555" cy="152.665" fill="url(#a)" rx="5.714" ry="5.714" data-v-04dc064e></ellipse><text font-family="Monospace" font-size="7" stroke="#666" stroke-dasharray="null" stroke-linecap="null" stroke-linejoin="null" stroke-width="0" text-anchor="middle" x="523.417" y="155.154" data-v-04dc064e>
          1
        </text></g><g fill-opacity=".31" data-v-04dc064e><ellipse cx="537.686" cy="152.666" fill="url(#a)" rx="5.714" ry="5.714" data-v-04dc064e></ellipse><text font-family="Monospace" font-size="8" stroke="#666" stroke-dasharray="null" stroke-linecap="null" stroke-linejoin="null" stroke-width="0" text-anchor="middle" x="537.549" y="155.154" data-v-04dc064e>
          2
        </text></g><path d="M223.386 34.209h183.096v20.788H223.386z" data-v-04dc064e></path><g fill-opacity=".31" data-v-04dc064e><ellipse cx="551.998" cy="152.665" fill="url(#a)" rx="5.714" ry="5.714" data-v-04dc064e></ellipse><text font-family="Monospace" font-size="7" stroke="#666" stroke-dasharray="null" stroke-linecap="null" stroke-linejoin="null" stroke-width="0" text-anchor="middle" x="551.86" y="155.154" data-v-04dc064e>
          3
        </text></g><g fill-opacity=".31" data-v-04dc064e><ellipse cx="523.827" cy="166.935" fill="url(#a)" rx="5.714" ry="5.714" data-v-04dc064e></ellipse><text font-family="Monospace" font-size="7" stroke="#666" stroke-dasharray="null" stroke-linecap="null" stroke-linejoin="null" stroke-width="0" text-anchor="middle" x="523.689" y="169.424" class="fourth" data-v-04dc064e>
          4
        </text></g><g fill-opacity=".31" data-v-04dc064e><ellipse cx="537.959" cy="166.935" fill="url(#a)" rx="5.714" ry="5.714" data-v-04dc064e></ellipse><text font-family="Monospace" font-size="7" stroke="#666" stroke-dasharray="null" stroke-linecap="null" stroke-linejoin="null" stroke-width="0" text-anchor="middle" x="537.821" y="169.424" data-v-04dc064e>
          5
        </text></g><g fill-opacity=".31" data-v-04dc064e><ellipse cx="552.27" cy="166.935" fill="url(#a)" rx="5.714" ry="5.714" data-v-04dc064e></ellipse><text font-family="Monospace" font-size="7" stroke="#666" stroke-dasharray="null" stroke-linecap="null" stroke-linejoin="null" stroke-width="0" text-anchor="middle" x="552.132" y="169.424" data-v-04dc064e>
          6
        </text></g><g fill-opacity=".31" data-v-04dc064e><ellipse cx="524.189" cy="181.609" fill="url(#a)" rx="5.714" ry="5.714" data-v-04dc064e></ellipse><text font-family="Monospace" font-size="7" stroke="#666" stroke-dasharray="null" stroke-linecap="null" stroke-linejoin="null" stroke-width="0" text-anchor="middle" x="524.052" y="184.097" data-v-04dc064e>
          7
        </text></g><g fill-opacity=".31" data-v-04dc064e><ellipse cx="538.321" cy="181.609" fill="url(#a)" rx="5.714" ry="5.714" data-v-04dc064e></ellipse><text font-family="Monospace" font-size="7" stroke="#666" stroke-dasharray="null" stroke-linecap="null" stroke-linejoin="null" stroke-width="0" text-anchor="middle" x="538.183" y="184.097" data-v-04dc064e>
          8
        </text></g><g fill-opacity=".31" data-v-04dc064e><ellipse cx="552.633" cy="181.609" fill="url(#a)" rx="5.714" ry="5.714" data-v-04dc064e></ellipse><text font-family="Monospace" font-size="7" stroke="#666" stroke-dasharray="null" stroke-linecap="null" stroke-linejoin="null" stroke-width="0" text-anchor="middle" x="552.495" y="184.097" data-v-04dc064e>
          9
        </text></g><g fill-opacity=".31" data-v-04dc064e><ellipse cx="538.321" cy="196.826" fill="url(#a)" rx="5.714" ry="5.714" data-v-04dc064e></ellipse><text font-family="Monospace" font-size="7" stroke="#666" stroke-dasharray="null" stroke-linecap="null" stroke-linejoin="null" stroke-width="0" text-anchor="middle" x="538.183" y="199.315" data-v-04dc064e>
          11
        </text></g><g fill-opacity=".31" data-v-04dc064e><ellipse cx="552.633" cy="196.826" fill="url(#a)" rx="5.714" ry="5.714" data-v-04dc064e></ellipse><text font-family="Monospace" font-size="7" stroke="#666" stroke-dasharray="null" stroke-linecap="null" stroke-linejoin="null" stroke-width="0" text-anchor="middle" x="552.495" y="199.315" data-v-04dc064e>
          12
        </text></g><g fill="#bf0000" fill-opacity=".31" data-v-04dc064e><ellipse cx="524.644" cy="212.678" rx="5.714" ry="5.714" data-v-04dc064e></ellipse><text font-family="Monospace" font-size="7" stroke="#666" stroke-dasharray="null" stroke-linecap="null" stroke-linejoin="null" stroke-width="0" text-anchor="middle" x="524.507" y="215.166" data-v-04dc064e>
          E
        </text></g><path fill="#666" d="M480.5 76.5h18v362h-18z" data-v-04dc064e></path><path fill="#333" d="M480.994 76h5.018v362.304h-5.018zM131.1 76.1h5v362.419h-5z" data-v-04dc064e></path><path fill="#666" d="M112.5 62.5h393v21h-393z" data-v-04dc064e></path><path fill="#333" d="M131.112 80.938h354.876v3.75H131.112z" data-v-04dc064e></path><text fill="#666" font-family="Monospace" font-size="11" stroke-dasharray="null" stroke-linecap="null" stroke-linejoin="null" stroke-width="0" text-anchor="middle" x="315.042" y="47.311" data-v-04dc064e>
        1 2 3 4 5 6 7 8 9 10 11 12
      </text><path fill="#CCC" d="M131.112 428.938h354.876v3.75H131.112z" data-v-04dc064e></path><path fill="#CCC" d="M131.112 430.938h354.876v3.75H131.112z" data-v-04dc064e></path><path fill="#DDD" d="M131.112 432.938h354.876v3.75H131.112z" data-v-04dc064e></path><path fill="#DDD" d="M131.112 434.938h354.876v3.75H131.112z" data-v-04dc064e></path></g></svg></div></div></div>
<!-- Elevator Interactive Activity -->

Unfortunately, and this is the most valuable lesson for protecting yourself from Phishing attacks, you cannot trust the buttons you click nor the way the website looks when you arrive.

You must be perpetually skeptical.

You are the target of a grand heist. They have switched the buttons inside the elevator and when the door opens it actually looks like your bank. You may think they redecorated a little, but in fact, the entire floor is a fake, designed entirely to dupe you.

While it would be far-fetched in the real world to build a fake bank, it is entirely possible to create a fake banking website.

How do you know you are actually on the website you want to be on?

You must check your address bar!

The difference between `https://chase.com-onlinebanking.com/`and `https://chase.com` could be your life savings.

## Takeaways

Don't trust what a link says.

Find the domain name in a URL.

Always check the URL in the address bar.

<!-- blank line -->
<figure class="video_container">
<iframe src="https://drive.google.com/file/d/1IYuuQaNgavj55wlotiXjivlYwYyIX54W/preview" width="640" height="480"></iframe>
</figure>
<!-- blank line -->

[← Fake Domains](./fake_domains.html "Fake Domains")

  
[Fake Emails →](./fake_emails.html "Fake Emails")
