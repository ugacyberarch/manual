---
layout: default
title: 'Phishing'
description: 'Fake Domains '

---
# Fake Domains

Since the "dot com boom" of the 90s, **domain names** have been an
ever-increasing part of daily life.

**What is a "domain name"?**

* facebook.com
* www.google.com
* www.bbc.co.uk
* en.wikipedia.org

Domain names, sometimes called _hostnames_, are the identifiers we give to
systems on the internet. For a few dollars a year, you can register your own
domain as easy as ordering a new pair of shoes.

One common way that phishing e-mails attempt to trick recipients is by using
domain names that look legitimate but actually lead to counterfeit websites
created solely to steal your information.

> **Phishing Domain**
>
> Here is an example of a domain that was used to phish for PayPal accounts:
>
> **paypal.com.9kcj.pw**

**How can you tell that `paypal.com.9kcj.pw` is a fake domain?**

You clearly see it contains `paypal.com`, and then you might think the rest is
just some technical bit you don't need to worry about.

Alas, the `paypal.com` at the beginning does _not_ mean PayPal owns the domain.
Anyone can add `paypal.com` to the _front_ of their domain name! The end of a
domain tells you who controls it.

> **Reading Domain Names**
>
> You must read domain names right-to-left, separating on the "dots", to
> understand ownership.
>
> For example, if you read `www.facebook.com` from right to left, you see that
> `com` controls `Facebook`, which controls `www`.

So, when you read the domain `paypal.com.9kcj.pw` from right to left, you see
that `pw` controls `9kcj`, which created a fake extension `paypal.com`.

Most companies use a single "top-level" domain, (e.g. `.com`, `.net`, or
`.org`).  Be wary if you expect the domain to end in `.com` but it actually
ends in something obscure, like `.pw`.

That may seem rather confusing, but it all becomes clear when you understand
how domains are created.

## Domain Hierarchy

Domains names are logically a tree. The first level of domains, called
"top-level domains", are actually the suffix of the domain name. You will
recognize many of them, such as `com`, `net`, and `org`.

The next level, "second-level", are what individuals and companies purchase.

All of the domains below this are controlled by whoever owns the second-level
domain.

Try adding `paypal.com` to the _beginning_ of any other domain. Does that
change the real `paypal.com`? Does it belong to PayPal?

<!--- Domain Hierarchy Interactive Activity -->
<div class="domains" data-v-48b68a03><!----><div class="form" data-v-48b68a03><form data-v-48b68a03><input placeholder="Enter a domain name" data-v-48b68a03><button data-v-48b68a03>Add</button></form></div><div class="list" data-v-48b68a03><ul data-v-48b68a03><li data-v-48b68a03>
        www.facebook.com
        <a data-v-48b68a03><i class="fas fa-times" data-v-48b68a03></i></a></li><li data-v-48b68a03>
        paypal.com
        <a data-v-48b68a03><i class="fas fa-times" data-v-48b68a03></i></a></li><li data-v-48b68a03>
        paypal.com.9kcj.pw
        <a data-v-48b68a03><i class="fas fa-times" data-v-48b68a03></i></a></li></ul><div style="clear:both;" data-v-48b68a03></div></div><svg id="tree" width="700" height="260" class="graph" data-v-48b68a03><g transform="translate(0,10)" data-v-48b68a03><g class="nodes" data-v-48b68a03><g class="node" data-v-48b68a03><circle cx="385" cy="0" r="2" fill="#696969" data-v-48b68a03></circle><text dx="395" dy="8" data-v-48b68a03>
            
 </text></g><g class="node" data-v-48b68a03><circle cx="210" cy="80" r="2" fill="#696969" data-v-48b68a03></circle><text dx="220" dy="88" data-v-48b68a03>
            com
          </text></g><g class="node" data-v-48b68a03><circle cx="560" cy="80" r="2" fill="#696969" data-v-48b68a03></circle><text dx="570" dy="88" data-v-48b68a03>
            pw
          </text></g><g class="node" data-v-48b68a03><circle cx="140" cy="160" r="2" fill="#696969" data-v-48b68a03></circle><text dx="150" dy="168" data-v-48b68a03>
            facebook
          </text></g><g class="node" data-v-48b68a03><circle cx="280" cy="160" r="2" fill="#696969" data-v-48b68a03></circle><text dx="290" dy="168" data-v-48b68a03>
            paypal
          </text></g><g class="node" data-v-48b68a03><circle cx="560" cy="160" r="2" fill="#696969" data-v-48b68a03></circle><text dx="570" dy="168" data-v-48b68a03>
            9kcj
          </text></g><g class="node" data-v-48b68a03><circle cx="140" cy="240" r="2" fill="#696969" data-v-48b68a03></circle><text dx="150" dy="248" data-v-48b68a03>
            www
          </text></g><g class="node" data-v-48b68a03><circle cx="560" cy="240" r="2" fill="#696969" data-v-48b68a03></circle><text dx="570" dy="248" data-v-48b68a03>
            paypal.com
          </text></g></g><g class="links" data-v-48b68a03><line stroke="#6f5f5f" x1="385" y1="0" x2="210" y2="80" class="link" data-v-48b68a03></line><line stroke="#6f5f5f" x1="385" y1="0" x2="560" y2="80" class="link" data-v-48b68a03></line><line stroke="#6f5f5f" x1="210" y1="80" x2="140" y2="160" class="link" data-v-48b68a03></line><line stroke="#6f5f5f" x1="210" y1="80" x2="280" y2="160" class="link" data-v-48b68a03></line><line stroke="#6f5f5f" x1="560" y1="80" x2="560" y2="160" class="link" data-v-48b68a03></line><line stroke="#6f5f5f" x1="140" y1="160" x2="140" y2="240" class="link" data-v-48b68a03></line><line stroke="#6f5f5f" x1="560" y1="160" x2="560" y2="240" class="link" data-v-48b68a03></line></g></g><rect width="700" height="260" style="fill: none; pointer-events: all;" data-v-48b68a03></rect></svg></div>
<!--- Domain Hierarchy Interactive Activity -->


## Phish / Not Phish

Adding a fake prefix is not the only trick criminals use. Below is a guessing
game. Would any of these phish fool you?

<!--- Phish/Not Phish Interactive Activity -->
<div class="guessing-game" data-v-2c3651d4><div domain="[object Object]" answers="[object Object]" class="menu" data-v-0fd62990 data-v-2c3651d4><div class="play" data-v-0fd62990><div class="logo" data-v-0fd62990><span data-v-0fd62990>phish</span><span data-v-0fd62990>not phish</span></div><button class="hvr-buzz" data-v-0fd62990>Play</button></div><div class="fishing" data-v-0fd62990><svg width="740" height="340" xmlns="http://www.w3.org/2000/svg" xmlns:svg="http://www.w3.org/2000/svg" data-v-0fd62990><g transform="scale(0.4)" data-v-0fd62990><g transform="scale(3)" class="hook" data-v-0fd62990><path d="M32,58c-8.271,0-15-6.729-15-15V21c0-6.104-2.369-10-4-10V7c4.561,0,8,6.019,8,14v22 c0,6.065,4.935,11,11,11s11-4.935,11-11v-1h-6l10-6.236V39v4C47,51.271,40.271,58,32,58z" style="fill:#C7CAC7;" data-v-0fd62990></path><path d="M22.648,27.937C22.765,27.979,22.883,28,23,28c0.404,0,0.786-0.248,0.937-0.649 c0.193-0.517-0.068-1.093-0.585-1.288L18,24.057v-1.863l4.648,1.743C22.765,23.979,22.883,24,23,24c0.404,0,0.786-0.248,0.937-0.649 c0.193-0.517-0.068-1.093-0.585-1.288L18,20.057V0h-2v19.307l-0.648-0.243c-0.519-0.192-1.095,0.067-1.288,0.585 c-0.193,0.517,0.068,1.093,0.585,1.288L16,21.443v1.863l-0.648-0.243c-0.519-0.192-1.095,0.067-1.288,0.585 c-0.193,0.517,0.068,1.093,0.585,1.288L16,25.443v1.863l-0.648-0.243c-0.519-0.192-1.095,0.067-1.288,0.585 c-0.193,0.517,0.068,1.093,0.585,1.288L16,29.443v1.863l-0.648-0.243c-0.519-0.191-1.095,0.068-1.288,0.585 c-0.193,0.517,0.068,1.093,0.585,1.288l1.308,0.491C15.74,35.43,14.06,37,12,37c-0.553,0-1,0.448-1,1s0.447,1,1,1 c2.915,0,5.348-2.09,5.887-4.849l4.762,1.786C22.765,35.979,22.883,36,23,36c0.404,0,0.786-0.248,0.937-0.649 c0.193-0.517-0.068-1.093-0.585-1.288L18,32.057v-1.863l4.648,1.743C22.765,31.979,22.883,32,23,32c0.404,0,0.786-0.248,0.937-0.649 c0.193-0.517-0.068-1.093-0.585-1.288L18,28.057v-1.863L22.648,27.937z" style="fill:#556080;" data-v-0fd62990></path></g><g class="bubbles" style="display:none;" data-v-0fd62990><path d="m152.23,178.782c0,7.458 -3.538,14.089 -9.041,18.309c-3.889,2.979 -8.751,4.758 -14.027,4.758c-12.744,0 -23.068,-10.334 -23.068,-23.068c0,-12.744 10.323,-23.078 23.068,-23.078c3.496,0 6.806,0.776 9.775,2.172c7.852,3.684 13.293,11.659 13.293,20.907z" fill="#C2DFF6" data-v-0fd62990></path><path d="m152.23,178.782c0,7.458 -3.538,14.089 -9.041,18.309c-7.862,-3.672 -13.303,-11.648 -13.303,-20.895c0,-7.469 3.548,-14.109 9.051,-18.32c7.852,3.683 13.293,11.658 13.293,20.906z" fill="#D1E7F8" data-v-0fd62990></path><path d="m208.761,88.663c0,7.469 -3.548,14.099 -9.041,18.309c-3.889,2.989 -8.751,4.758 -14.027,4.758c-12.744,0 -23.078,-10.323 -23.078,-23.068s10.334,-23.068 23.078,-23.068c3.496,0 6.796,0.776 9.765,2.172c7.851,3.665 13.303,11.651 13.303,20.897z" fill="#C2DFF6" data-v-0fd62990></path><path d="m208.761,88.663c0,7.469 -3.548,14.099 -9.041,18.309c-7.862,-3.662 -13.313,-11.637 -13.313,-20.895c0,-7.469 3.548,-14.109 9.051,-18.309c7.851,3.663 13.303,11.649 13.303,20.895z" fill="#D1E7F8" data-v-0fd62990></path></g><g transform="translate(0,1400)" class="fishy" data-v-0fd62990><g data-v-0fd62990><path d="m231.975,473.797c-20.037,-12.051 -29.75,-38.987 -34.063,-54.783c6.579,0.238 13.406,0.434 20.481,0.579c6.455,0.134 13.137,0.228 20.016,0.279l0.414,0l0.083,1.003l2.876,36.122l0.641,8.079c0.558,6.839 -5.348,11.794 -10.448,8.721z" fill="#1A6FB0" data-v-0fd62990></path><path d="m411.861,436.434c-11.875,1.014 -43.394,-5.358 -65.499,-35.832c7.334,-2.214 14.285,-4.417 20.781,-6.486c6.962,-2.214 13.406,-4.262 19.251,-5.958c3.9,8.472 10.592,21.63 17.296,31.964c3.289,5.079 6.589,9.486 9.548,12.299c1.457,1.387 0.64,3.837 -1.377,4.013z" fill="#1A6FB0" data-v-0fd62990></path></g><g data-v-0fd62990><path d="m241.781,456.998c-11.441,-9.879 -18.785,-24.712 -23.388,-37.405c6.455,0.134 13.137,0.228 20.016,0.279l0.414,0l0.083,1.003l2.875,36.123z" fill="#1E81CE" data-v-0fd62990></path><path d="m403.689,420.122c-11.689,-4.355 -25.054,-12.341 -36.546,-26.005c6.962,-2.214 13.406,-4.262 19.251,-5.958c3.899,8.471 10.592,21.629 17.295,31.963z" fill="#1E81CE" data-v-0fd62990></path><path d="m374.382,289.03l-5.648,6.734l-19.675,23.461c-64.01,-50.097 -130.947,-67.475 -188.068,-46.001c11.13,-12.558 20.057,-23.347 28.612,-31.891c14.823,-14.823 28.488,-22.871 50.469,-21.568c33.577,1.976 83.84,12.175 132.571,49.569c5.651,4.334 6.509,14.006 1.739,19.696z" fill="#1A6FB0" data-v-0fd62990></path></g><g class="tail animated shake infinite" data-v-0fd62990><path d="m411.235,338.391l72.607,-50.269c8.096,-5.606 19.157,0.189 19.157,10.037l0,129.515c0,9.617 -10.602,15.457 -18.731,10.319l-72.607,-45.892c-3.54,-2.237 -5.685,-6.132 -5.685,-10.319l0,-33.355c0,-4.005 1.965,-7.756 5.259,-10.036z" fill="#1A6FB0" data-v-0fd62990></path></g><path d="m368.736,295.764l-19.675,23.461c-64.01,-50.097 -130.947,-67.475 -188.068,-46.001c11.13,-12.558 20.057,-23.347 28.612,-31.891c9.134,-4.634 19.282,-6.796 32.026,-6.041c36.049,2.11 90.036,13.003 142.388,52.921c2.399,1.821 3.993,4.551 4.717,7.551z" fill="#165C92" data-v-0fd62990></path><path d="m435.331,374.07c-3.6,21.423 -24.185,13.044 -43.652,18.526c-32.026,9.041 -83.602,29.884 -138.25,29.884c-22.954,0 -70.62,-0.61 -115.927,-5.565c-58.269,-6.382 -112.628,-19.964 -105.469,-48.69c1.241,-4.965 6.734,-7.541 11.337,-5.307c1.593,0.776 3.434,1.624 5.451,2.524c1.138,-2.721 2.327,-5.389 3.569,-8.017c10.613,-22.437 24.898,-41.418 41.946,-56.728c11.41,-10.251 24.061,-18.857 37.674,-25.747c9.103,-4.603 18.63,-8.451 28.509,-11.503c70.506,-21.837 156.032,4.665 232.568,70.061c12.041,10.282 26.554,11.037 35.253,16.768c6.019,3.953 9.267,10.284 6.991,23.794z" fill="#3D9AE2" data-v-0fd62990></path><path d="m428.339,350.279c-8.586,2.824 -20.761,1.076 -32.522,4.396c-32.026,9.03 -83.602,29.874 -138.25,29.874c-22.954,0 -70.62,-0.6 -115.927,-5.565c-35.574,-3.9 -69.699,-10.468 -89.25,-21.557c10.613,-22.437 24.898,-41.418 41.946,-56.728c11.41,-10.251 24.061,-18.857 37.674,-25.747c9.103,-4.603 18.63,-8.451 28.509,-11.503c70.506,-21.837 156.032,4.665 232.568,70.061c12.039,10.283 26.551,11.037 35.252,16.769z" fill="#5AAAE7" data-v-0fd62990></path><path d="m164.055,348.702c0,26.3 -10.067,50.254 -26.554,68.21c-58.27,-6.382 -112.631,-19.956 -105.467,-48.688c1.237,-4.964 6.732,-7.539 11.333,-5.306c1.6,0.777 3.44,1.625 5.453,2.524c10.869,-25.955 26.47,-47.641 45.513,-64.744c11.414,-10.248 24.064,-18.854 37.676,-25.744c19.717,18.413 32.046,44.642 32.046,73.748z" fill="#78B9EB" data-v-0fd62990></path><circle cx="105.252" cy="338.563" fill="#1A6FB0" r="12.979" data-v-0fd62990></circle><g data-v-0fd62990><path d="m220.228,339.076c-4.285,0 -7.758,-3.473 -7.758,-7.758c0,-4.286 3.474,-7.758 7.758,-7.758c2.779,0 5.04,-2.261 5.04,-5.039c0,-2.779 -2.261,-5.04 -5.04,-5.04c-4.285,0 -7.758,-3.473 -7.758,-7.758c0,-4.286 3.474,-7.758 7.758,-7.758c2.779,0 5.04,-2.261 5.04,-5.04c0,-2.778 -2.261,-5.04 -5.04,-5.04c-4.285,0 -7.758,-3.473 -7.758,-7.758c0,-4.286 3.474,-7.758 7.758,-7.758c11.335,0 20.556,9.222 20.556,20.556c0,4.835 -1.678,9.284 -4.481,12.798c2.803,3.514 4.481,7.963 4.481,12.798c0,11.334 -9.221,20.555 -20.556,20.555z" fill="#78B9EB" data-v-0fd62990></path><path d="m282.57,374.88c-4.285,0 -7.758,-3.473 -7.758,-7.758c0,-4.286 3.474,-7.758 7.758,-7.758c2.779,0 5.04,-2.261 5.04,-5.04c0,-2.778 -2.261,-5.04 -5.04,-5.04c-4.285,0 -7.758,-3.473 -7.758,-7.758c0,-4.286 3.474,-7.758 7.758,-7.758c2.779,0 5.04,-2.261 5.04,-5.039c0,-2.78 -2.261,-5.04 -5.04,-5.04c-4.285,0 -7.758,-3.473 -7.758,-7.758c0,-4.286 3.474,-7.758 7.758,-7.758c11.335,0 20.556,9.222 20.556,20.556c0,4.834 -1.677,9.284 -4.481,12.797c2.803,3.514 4.481,7.963 4.481,12.798c-0.001,11.334 -9.222,20.556 -20.556,20.556z" fill="#78B9EB" data-v-0fd62990></path><path d="m324.815,379.287c-4.285,0 -7.758,-3.473 -7.758,-7.758s3.474,-7.758 7.758,-7.758c2.778,0 5.04,-2.261 5.04,-5.039c0,-2.78 -2.261,-5.04 -5.04,-5.04c-4.285,0 -7.758,-3.473 -7.758,-7.758s3.474,-7.758 7.758,-7.758c2.778,0 5.04,-2.261 5.04,-5.04c0,-2.778 -2.261,-5.04 -5.04,-5.04c-4.285,0 -7.758,-3.473 -7.758,-7.758c0,-4.286 3.474,-7.758 7.758,-7.758c11.334,0 20.556,9.222 20.556,20.556c0,4.835 -1.677,9.284 -4.481,12.798c2.803,3.514 4.481,7.963 4.481,12.798c0,11.334 -9.222,20.555 -20.556,20.555z" fill="#78B9EB" data-v-0fd62990></path></g><path d="m266.794,401.895c-12.392,2.152 -29.936,1.821 -52.466,-6.713c-2.896,-1.096 -4.924,-3.755 -5.265,-6.837l-1.272,-11.461l-0.248,-2.245c-0.641,-5.782 4.676,-10.417 10.313,-8.979c12.279,3.124 32.45,8.937 51.307,17.337c1.386,0.621 2.514,1.448 3.393,2.431c4.882,5.368 2.441,15.05 -5.762,16.467z" fill="#1A6FB0" data-v-0fd62990></path><path d="m272.555,385.428c-15.465,1.386 -36.174,0.3 -61.982,-7.313c-1.024,-0.3 -1.955,-0.724 -2.783,-1.231l-0.248,-2.245c-0.641,-5.782 4.676,-10.417 10.313,-8.979c12.279,3.124 32.45,8.937 51.307,17.337c1.387,0.621 2.514,1.447 3.393,2.431z" fill="#1E81CE" data-v-0fd62990></path><path d="m141.638,378.984c-35.574,-3.9 -69.699,-10.468 -89.25,-21.557c-1.241,2.627 -2.431,5.296 -3.569,8.017c-2.017,-0.9 -3.858,-1.748 -5.451,-2.524c-4.603,-2.234 -10.096,0.341 -11.337,5.307c-7.158,28.726 47.201,42.308 105.469,48.69c9.486,-10.324 16.84,-22.643 21.381,-36.246c-5.749,-0.499 -11.511,-1.057 -17.243,-1.687z" fill="#5AAAE7" data-v-0fd62990></path><path d="m137.501,416.915c-58.269,-6.382 -112.628,-19.964 -105.469,-48.69c1.169,-4.655 6.072,-7.21 10.479,-5.669c10.154,5.085 34.057,12.26 44.914,15.413c5.901,1.718 11.85,3.258 17.841,4.621c12.74,2.896 23.847,10.881 30.393,22.187c2.839,4.903 4.242,9.524 1.842,12.138z" fill="#96C8EF" data-v-0fd62990></path></g></g></svg></div></div></div>
<!--- Phish/Not Phish Interactive Activity -->


## Takeaways

Don't trust a domain simply because it starts with an official name.

Domain ownership is applied right-to-left, and if you are ever in doubt think
about it as a tree.

Be wary of domains that end in a top-level you didn't expect (e.g. `.co`
instead of `.com`).




 <span style="float:left;"> 
<a href="/phishing_introduction.html">← Introduction</a>
  </span> 
 <span style="float:right;">
  <a href="./fake_links.html ">Fake Links →</a>
  </span> 
<br />
<br />

