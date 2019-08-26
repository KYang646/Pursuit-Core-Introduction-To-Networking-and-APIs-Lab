# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200
```
http://www.google.com
```
1. 301
```
https://httpstatuses.com/301
```
1. 400
```
https://httpstat.us/400
```
1. 401
```
https://httpstat.us/401
```
1. 403
```
https://httpstat.us/403
```
1. 404
```
https://www.raywenderlich.com/efeff
```
1. 418
```
https://httpstat.us/418
```
1. 500
```
https://httpstatuses.com/500
```


For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat


# Part Two

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact
https://catfact.ninja
```

{
"total": 98,
"per_page": "1",
"current_page": 1,
"last_page": 98,
"next_page_url": "https://catfact.ninja/breeds?page=2",
"prev_page_url": null,
"from": 1,
"to": 1,
"data": [
{
"breed": "Abyssinian",
"country": "Ethiopia",
"origin": "Natural/Standard",
"coat": "Short",
"pattern": "Ticked"
}
]
}
```
1. A list of 150 random users in English.
https://randomuser.me
```

<!DOCTYPE html><html lang="en"><head><title>Random User Generator | Home</title><meta charset='utf-8'><meta name="description" content="Random user generator is a FREE API for generating placeholder user information. Get profile photos, names, and more. It's like Lorem Ipsum, for people."><meta name="apple-mobile-web-app-capable" content="yes"><meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no"><link rel="stylesheet" type="text/css" href="dist/style.css"><script src="dist/all.js"></script></head><body class=""><div id="navbar" class=""><div class="nav_toggle"><div class="icon"><div></div><div></div><div></div></div></div><ul><li><a href="index">Home</a></li><li><a href="photos">User Photos</a></li><li><a href="documentation">Documentation</a></li><li><a href="changelog">Change Log</a></li><li><a href="stats">Stats &amp; Graphs</a></li><li><a href="donate">Donate</a></li><li><a href="copyright">Copyright Notice</a></li><li class="blank"></li><li><a href="photoshop">Photoshop Extension</a></li></ul></div><header><h1>Random User Generator</h1><p>A free, <a id="openSource" href="https://github.com/RandomAPI/Randomuser.me-Node">open-source</a> API for generating random user data. Like Lorem Ipsum, but for people. </p><a href="https://twitter.com/randomapi" class="twitter"><img src="img/twitter.png">Follow us @randomapi</a></header><div class="frame card_offset"><div class="card"><div class="details"><div class="user_photo horizontal_center" id="user_photo"><a href="javascript:getNewUser();" class="refresh">New</a><img src=""></div><p id="user_title">Hi, My name is</p><p id="user_value">...</p></div><ul class="values_list horizontal_center" id="values_list"><li data-title="Hi, My name is" data-value="..." data-label="name" class="active"></li><li data-title="My email address is" data-value="..." data-label="email" data-caps="false"></li><li data-title="My birthday is" data-value="..." data-label="birthday"></li><li data-title="My address is" data-value="..." data-label="location"></li><li data-title="My phone number is" data-value="..." data-label="phone"></li><li data-title="My password is" data-value="..." data-label="pass" data-caps="false"></li></ul></div><section class="sponsor"><h2>Sponsored</h2><h3>RandomAPI</h3><p>Want to create your own <b>customized</b> data generator for your application?<br>Check out our other service RandomAPI!</p><button id="learnmore" class="button" onClick="window.open('https://randomapi.com');">Learn More</button></section><section class="advertisement"><script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:inline-block;width:230px;height:200px" data-ad-client="ca-pub-2036801804961954" data-ad-slot="7646598623"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script><ins class="adsbygoogle" style="display:inline-block;width:230px;height:200px;margin:0 16px;" data-ad-client="ca-pub-2036801804961954" data-ad-slot="7646598623"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script><ins class="adsbygoogle" style="display:inline-block;width:230px;height:200px" data-ad-client="ca-pub-2036801804961954" data-ad-slot="7646598623"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script></section><section><h2>How to use</h2><p>You can use AJAX to call the Random User Generator API and will receive a randomly generated user in return. If you are using jQuery, you can use the $.ajax() function in the code snippet below to get started.</p><pre>$.ajax({
url: '<span>https: //randomuser.me/api/</span>',
dataType: '<span>json</span>',
success: function(<span>data</span>) {
console.log(<span>data</span>);
}
});
</pre></section><section><h2>Results</h2><p>The application will provide you with a JSON, XML, CSV, or YAML object that you can parse and apply to your application.</p><p>You can specify the format you want the results in using the <a href="documentation#format">format</a> parameter.</p><pre>{
"results": [
{
"gender": "<span>male</span>",
"name": {
"title": "<span>mr</span>",
"first": "<span>rolf</span>",
"last": "<span>hegdal</span>"
},
"location": {
"street": "<span>ljan terrasse 346</span>",
"city": "<span>vear</span>",
"state": "<span>rogaland</span>",
"postcode": "<span>3095</span>",
"coordinates": {
"latitude": "<span>54.8646</span>",
"longitude": "<span>-97.3136</span>"
},
"timezone": {
"offset": "<span>-10:00</span>",
"description": "<span>Hawaii</span>"
}
},
"email": "<span><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="13617c7f753d7b767477727f53766b727e637f763d707c7e">[email&#160;protected]</a></span>",
"login": {
"uuid": "<span>c4168eac-84b8-46ea-b735-c9da9bfb97fd</span>",
"username": "<span>bluefrog786</span>",
"password": "<span>ingrid</span>",
"salt": "<span>GtRFz4NE</span>",
"md5": "<span>5c581c5748fc8c35bd7f16eac9efbb55</span>",
"sha1": "<span>c3feb8887abed9ec1561b9aa2c9f58de21d1d3d9</span>",
"sha256": "<span>684c478a98b43f1ef1703b35b8bbf61b27dbc93d52acd515e141e97e04447712</span>"
},
"dob": {
"date": "<span>1975-11-12T06:34:44Z</span>",
"age": <span>42</span>
},
"registered": {
"date": <span>"2015-11-04T22:09:36Z</span>",
"age": <span>2</span>
},
"phone": "<span>66976498</span>",
"cell": "<span>40652479</span>",
"id": {
"name": "<span>FN</span>",
"value": "<span>12117533881</span>"
},
"picture": {
"large": "<span>https://randomuser.me/api/portraits/men/65.jpg</span>",
"medium": "<span>https://randomuser.me/api/portraits/med/men/65.jpg</span>",
"thumbnail": "<span>https://randomuser.me/api/portraits/thumb/men/65.jpg</span>"
},
"nat": "<span>NO</span>"
}
],
"info": {
"seed": "<span>2da87e9305069f1d</span>",
"results": <span>1</span>,
"page": <span>1</span>,
"version": "<span>1.2</span>"
}
}
</pre></section><section><h2>Thank you for helping us help you help us all</h2><p>Found a bug or have an idea?<br>Contribute to randomuser.me's database on our <a href="https://github.com/RandomAPI/Randomuser.me-Node">Github Repo</a>.</p><h2>Contact Us</h2><p>If you have any questions/feedback or would like to get in touch with us, tweet us <a href="https://twitter.com/randomapi">@randomapi</a></p></section><section class="cheat"><p>&uarr; &uarr; &darr; &darr; &larr; &rarr; &larr; &rarr; B A</p></section></div><footer><div class="frame"><h1>Random User Generator</h1><div class="block"><div class="builder"><h3>Designed</h3><a href="https://twitter.com/arronhunt"><img src="img/creator_arron.png" width="80px" alt="Designed by Arron Hunt" title="Designed by Arron Hunt" /></a></div><div class="builder"><h3>Developed</h3><a href="https://twitter.com/solewolf1993"><img src="img/creator_keith.png" width="80px" alt="Developed by Keith Armstrong" title="Developed by Keith Armstrong" /></a></div></div><div class="block"><h3>Copyright Notice</h3><p>All randomly generated photos were hand picked from the authorized section of <a href="http://uifaces.com">UI Faces</a>. Please visit <a href="https://web.archive.org/web/20160811185628/http://uifaces.com/faq">UI Faces FAQ</a> for more information regarding how you can use these faces.<br><br></div></div></footer><script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script>(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject'
]=r;i[r
]=i[r
]||function(){(i[r
].q=i[r
].q||[]).push(arguments)
},i[r
].l=1*new Date();a=s.createElement(o),m=s.getElementsByTagName(o)[
0
];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
})(window,document,'script',' //www.google-analytics.com/analytics.js','ga');ga('create', 'UA-42942064-1', 'randomuser.me');ga('send', 'pageview');</script></body></html>"
```
1. The current stock price of Microsoft. (IEX API)
https://iextrading.com/?gclid=EAIaIQobChMIrIKJ7Jyh5AIVDT0MCh09JQGWEAAYASAAEgIZgfD_BwE
```
<!doctype html>

<!--
___________________
|                   |
|    ___________    |
|   |           |   |
|   |           |   |
|   |           |   |
|   |___        |   |
|       |       |   |
|       |_______|   |
|                   |
|___________________|

-->

<html class="page--home

" lang="en-US">

<head>
<meta charset="utf-8">
<meta http-equiv="x-ua-compatible" content="ie=edge">

<title>IEX Group | IEX</title>
<meta name="description" content="IEX, the Investors Exchange, is a fair, simple and transparent stock exchange dedicated to investor and issuer protection.">

<meta property="og:title" content="IEX Group | IEX">
<meta property="og:description" content="IEX, the Investors Exchange, is a fair, simple and transparent stock exchange dedicated to investor and issuer protection.">
<meta property="og:type" content="article">
<meta property="og:image" content="https://iextrading.com/images/iex/iex-card.png">

<meta name="twitter:card" content="summary">
<meta name="twitter:site" content="@iex">
<meta name="twitter:title" content="IEX Group | IEX">
<meta name="twitter:description" content="IEX, the Investors Exchange, is a fair, simple and transparent stock exchange dedicated to investor and issuer protection.">
<meta name="twitter:creator" content="@iex">
<meta name="twitter:image" content="https://iextrading.com/images/iex/iex-card.png">

<meta name="viewport" content="width=device-width, initial-scale=1">

<meta name="apple-mobile-web-app-title" content="IEX">

<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png?v=8jeB9gR7PE">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png?v=8jeB9gR7PE">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png?v=8jeB9gR7PE">
<link rel="manifest" href="/manifest.json?v=8jeB9gR7PE">
<link rel="mask-icon" href="/safari-pinned-tab.svg?v=8jeB9gR7PE" color="#ffa200">
<link rel="shortcut icon" href="/favicon.ico?v=8jeB9gR7PE">
<meta name="msapplication-TileColor" content="#ffa200">
<meta name="msapplication-TileImage" content="/mstile-144x144.png?v=8jeB9gR7PE">
<meta name="theme-color" content="#f1f1f1">

<link rel="stylesheet" href="/build/app.min.css">

<!-- Google Tag Manager -->

<script>(function (w, d, s, l, i) {
w[l
] = w[l
] || []; w[l
].push({
'gtm.start':

new Date().getTime(), event: 'gtm.js'
}); var f = d.getElementsByTagName(s)[
0
],

j = d.createElement(s), dl = l != 'dataLayer' ? '&l=' + l : ''; j.async = true; j.src =

'https: //www.googletagmanager.com/gtm.js?id=' + i + dl; f.parentNode.insertBefore(j, f);
})(window, document, 'script', 'dataLayer', 'GTM-NFT68CD');</script>

<!-- End Google Tag Manager -->

<!-- Request only ampersand: chrisnager.com/tiny-google-fonts -->
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Libre+Baskerville:400italic&text=%26">
</head>



<body>
<!-- Google Tag Manager (noscript) -->

<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-NFT68CD" height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>

<!-- End Google Tag Manager (noscript) -->

<div class="relative col-12">
<div class="fixed z1 col-12 bottom-0 hide right-0" id="cookies-popup">
<div class="p2 md-col-6 lg-col-3 m2 border-light bg-silver animated fadeInUp delay-1s rounded bottom-0 right" style="box-shadow: 0px 4px 8px 0px rgba(130,132,136,.2);">
<div class="flex flex-justify flex-center">
<div class="h6 flex-1 border-box mr3 black">We use cookies to understand how this site is used and to improve your user experience. By using this site, you consent to the use of cookies. For more information and to learn how to manage your cookie preferences, please see our <a href="/privacy/">Privacy Notice</a>.</div>
<div class="border-box">
<button class="btn btn-primary m0" style="font-size: 12px;" id="cookies-btn">OK</button>
</div>
</div>
</div>
</div>
</div>
<header class="nav relative bg-silver header-home" style="z-index: 9999;">
<nav class="clearfix container px2 z1 border-box">
<a class="btn block border-box left relative z1 fill-orange bg-light-orange bg-clip-content logo" style="margin: 14px; padding: 4px;"
href="/">
<svg
class="align-middle"
xmlns="http://www.w3.org/2000/svg"
viewBox="0 0 5 5"
width="28"
height="28"
>
<title>IEX logo</title>
<path d="M0,0v5h5V0z M1,1h3v3H2V3H1z" />
</svg>
```
1. The 5 year history of Apple stock prices (IEX API)
https://iextrading.com/apps/stocks/AAPL
```
<!doctype html>

<!--
___________________
|                   |
|    ___________    |
|   |           |   |
|   |           |   |
|   |           |   |
|   |___        |   |
|       |       |   |
|       |_______|   |
|                   |
|___________________|

-->

<html class="page--apps-stocks

" lang="en-US">

<head>
<meta charset="utf-8">
<meta http-equiv="x-ua-compatible" content="ie=edge">

<title>Stocks | IEX</title>
<meta name="description" content="Free, real time stock quotes, charts, trading analyses, financial news, and market overview.">

<meta property="og:title" content="Stocks | IEX">
<meta property="og:description" content="Free, real time stock quotes, charts, trading analyses, financial news, and market overview.">
<meta property="og:type" content="article">
<meta property="og:image" content="https://iextrading.com/images/iex/iex-card.png">

<meta name="twitter:card" content="summary">
<meta name="twitter:site" content="@iex">
<meta name="twitter:title" content="Stocks | IEX">
<meta name="twitter:description" content="Free, real time stock quotes, charts, trading analyses, financial news, and market overview.">
<meta name="twitter:creator" content="@iex">
<meta name="twitter:image" content="https://iextrading.com/images/iex/iex-card.png">

<meta name="viewport" content="width=device-width, initial-scale=1">

<meta name="apple-mobile-web-app-title" content="Stocks">

<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png?v=8jeB9gR7PE">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png?v=8jeB9gR7PE">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png?v=8jeB9gR7PE">
<link rel="manifest" href="/manifest.json?v=8jeB9gR7PE">
<link rel="mask-icon" href="/safari-pinned-tab.svg?v=8jeB9gR7PE" color="#ffa200">
<link rel="shortcut icon" href="/favicon.ico?v=8jeB9gR7PE">
<meta name="msapplication-TileColor" content="#ffa200">
<meta name="msapplication-TileImage" content="/mstile-144x144.png?v=8jeB9gR7PE">
<meta name="theme-color" content="#f1f1f1">

<link rel="stylesheet" href="/build/app.min.css">

<!-- Google Tag Manager -->

<script>(function (w, d, s, l, i) {
w[l
] = w[l
] || []; w[l
].push({
'gtm.start':

new Date().getTime(), event: 'gtm.js'
}); var f = d.getElementsByTagName(s)[
0
],

j = d.createElement(s), dl = l != 'dataLayer' ? '&l=' + l : ''; j.async = true; j.src =

'https: //www.googletagmanager.com/gtm.js?id=' + i + dl; f.parentNode.insertBefore(j, f);
})(window, document, 'script', 'dataLayer', 'GTM-NFT68CD');</script>

<!-- End Google Tag Manager -->

<!-- Request only ampersand: chrisnager.com/tiny-google-fonts -->
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Libre+Baskerville:400italic&text=%26">
</head>

<body>
<!-- Google Tag Manager (noscript) -->

<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-NFT68CD" height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>

<!-- End Google Tag Manager (noscript) -->

<main class="relative">

<div id="app">
<div class="shadow-small bg-white mxn1">
<div class="container border-box clearfix md-px3 px2">
<div class="flex flex-justify align-items-center">
<div style="margin-left:4px;">
<a class="block border-box left relative z1 fill-orange bg-light-orange bg-clip-content logo" style="margin:
14px 16px 14px 0px; padding: 4px 0px;" href="/">
<svg class="align-middle" viewBox="0 0 5 5" width="28" height="28">
<title>IEX home</title>
<path d="M0,0v5h5V0z M1,1h3v3H2V3H1z" />
</svg>
</a>
<a href="/" class="h6 md-show nowrap no-underline-on-hover black blue-on-hover" style="
margin: 20px 8px 16px 8px; padding: 4px;">

<p class="mb0 mt0 align-middle">
<b>IEX</b> Stocks</p>
</a>
</div>
</div>
</div>
</div>
<div style="min-height: 100vh; background: #fafafa;">&nbsp;</div>
</div>
<style>
.shadow-small {
box-shadow: 0px 1px 10px 1px rgba(210,
210,
210,.15);
-webkit-box-shadow: 0px 1px 10px 1px rgba(210,
210,
210,.15);
-moz-box-shadow: 0px 1px 10px 1px rgba(210,
210,
210,.15);
-ms-box-shadow: 0px 1px 10px 1px rgba(210,
210,
210,.15);
-o-box-shadow: 0px 1px 10px 1px rgba(210,
210,
210,.15);
}
</style>

<section class="bg-black">
<a class="block white bold py2 px3 container border-box" href="https://iexcloud.io/">Build your own apps with IEX Cloud &raquo;</a>
</section>

</main>

<footer class="footer dark-gray relative border-top-light">
<section id="contact" style="background-color: #f8f8f8;">
<div class="container border-box p3 clearfix">
<div class="md-col md-col-4">
<h2 class="h4">Sales</h2>
<p class="h5 mb0 footer-contact-link"><a class="mid-gray key-on-hover no-underline-on-hover" href="tel:6463432110">646.343.2110</a></p>
<p class="h5 md-mb3 footer-contact-link"><a class="mid-gray key-on-hover no-underline-on-hover" href="mailto:sales@iextrading.com">sales@iextrading.com</a></p>
<h2 class="h4">Listings</h2>
<p class="h5 mb0 footer-contact-link"><a class="mid-gray key-on-hover no-underline-on-hover" href="tel:6463432140">646.343.2140</a></p>
<p class="h5 footer-contact-link"><a class="mid-gray key-on-hover no-underline-on-hover" href="mailto:listings@iextrading.com">listings@iextrading.com</a></p>
</div>
<div class="md-col md-col-4">
<h2 class="h4">Technology & Network Operations</h2>
<p class="h5 mb0 footer-contact-link"><a class="mid-gray key-on-hover no-underline-on-hover" href="tel:6463432200">646.343.2200</a></p>
<p class="h5 md-mb3 footer-contact-link"><a class="mid-gray key-on-hover no-underline-on-hover" href="mailto:sre@iextrading.com">sre@iextrading.com</a></p>
<h2 class="h4">Market Operations</h2>
<p class="h5 mb0 footer-contact-link"><a class="mid-gray key-on-hover no-underline-on-hover" href="mailto:marketops@iextrading.com">marketops@iextrading.com</a></p>
</div>
<div class="md-col md-col-4">
<h2 class="h4">Marketing & Communications</h2>
<p class="h5 mb0 footer-contact-link"><a class="mid-gray key-on-hover no-underline-on-hover" href="tel:6463432130">646.343.2130</a></p>
<p class="h5 md-mb3 footer-contact-link"><a class="mid-gray key-on-hover no-underline-on-hover" href="mailto:marcomms@iextrading.com">marcomms@iextrading.com</a></p>
<h2 class="h4">IEX Cloud<sup>*</sup></h2>
<p class="h5 mb0 footer-contact-link"><a class="mid-gray key-on-hover no-underline-on-hover" href="https://iexcloud.io/support/">Support</a></p>
<p class="h5 md-mb3 footer-contact-link"><a class="mid-gray key-on-hover no-underline-on-hover" href="mailto:support@iexcloud.io">support@iexcloud.io</a></p>
</div>
</div>
</section>
```
1. All the Swift language repos on Github with Pursuit in their name
https://github.com/joinpursuit
```

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<link rel="dns-prefetch" href="https://github.githubassets.com">
<link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
<link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
<link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
<link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
<link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
<link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



<link crossorigin="anonymous" media="all" integrity="sha512-UDS3MR1FfvqHmqZAs2MWSDCWPwLemVRLqCwld4/zfwH0vhv7I6RYmDnMnNAVQKP1YYvqnccOCH4iOhFaUUyrjw==" rel="stylesheet" href="https://github.githubassets.com/assets/frameworks-2e9090135c22aad5f56c2f72dcba7880.css" />
<link crossorigin="anonymous" media="all" integrity="sha512-l4JpykYR1c86XfE0TExTqRFbnoD7WA39FhTTEgPt22zLFiepYq+L+3XUGBZoGsnBv15oKHTomwpEAUrCbmoRqw==" rel="stylesheet" href="https://github.githubassets.com/assets/site-2f0f446a127a5a480dfb139991acd1cd.css" />
<link crossorigin="anonymous" media="all" integrity="sha512-ip0PbDWWMX/xpzE2prEhR95RqVx8aDPUKvBEz691/7Isc3uapauorbb1zFXT2I5Go5BTzaev9qh/wKMj9pH95A==" rel="stylesheet" href="https://github.githubassets.com/assets/github-cbb49d8cd46cbc8c522a95d52b21ab53.css" />





<meta name="viewport" content="width=device-width">

<title>Pursuit · GitHub</title>
<meta name="description" content="Pursuit is a social impact organization that creates transformation where it’s needed most. - Pursuit">
<link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
<link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
<meta property="fb:app_id" content="1401488693436528">

<meta name="twitter:image:src" content="https://avatars0.githubusercontent.com/u/5825944?s=280&amp;v=4" /><meta name="twitter:site" content="@github" /><meta name="twitter:card" content="summary_large_image" /><meta name="twitter:title" content="Pursuit" /><meta name="twitter:description" content="Pursuit is a social impact organization that creates transformation where it’s needed most. - Pursuit" />
<meta property="og:image" content="https://avatars0.githubusercontent.com/u/5825944?s=280&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="profile" /><meta property="og:title" content="Pursuit" /><meta property="og:url" content="https://github.com/joinpursuit" /><meta property="og:description" content="Pursuit is a social impact organization that creates transformation where it’s needed most. - Pursuit" /><meta property="profile:username" content="joinpursuit" />

<link rel="assets" href="https://github.githubassets.com/">

<meta name="pjax-timeout" content="1000">

<meta name="request-id" content="1663:624C:7FE4F:A9C44:5D643147" data-pjax-transient>

<meta name="hovercard-subject-tag" content="organization:5825944" data-pjax-transient>



<meta name="selected-link" value="/joinpursuit" data-pjax-transient>

<meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
<meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
<meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

<meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="1663:624C:7FE4F:A9C44:5D643147" /><meta name="octolytics-dimension-region_edge" content="iad" /><meta name="octolytics-dimension-region_render" content="iad" /><meta name="octolytics-dimension-ga_id" content="" class="js-octo-ga-id" /><meta name="octolytics-dimension-visitor_id" content="3415015231186022727" />
<meta name="analytics-location" content="/&lt;org-login&gt;" data-pjax-transient="true" />



<meta name="google-analytics" content="UA-3769691-2">


<meta class="js-ga-set" name="dimension1" content="Logged Out">
```
1. A list of all Pokemon
https://pokeapi.co
```

<!DOCTYPE html><html lang="en"><head><meta charSet="utf-8"/><meta http-equiv="x-ua-compatible" content="ie=edge"/><meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no"/><style data-href="/styles.60137468abe8abceed3e.css"> /*! sanitize.css v7.0.3 | CC0 License | github.com/csstools/sanitize.css */*,
:after,
:before{background-repeat:no-repeat;box-sizing:border-box
}:after,
:before{text-decoration:inherit;vertical-align:inherit
}html{cursor:default;font-family:system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Cantarell,Oxygen,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji;line-height: 1.15;-moz-tab-size: 4;-o-tab-size: 4;tab-size: 4;-ms-text-size-adjust: 100%;-webkit-text-size-adjust: 100%;word-break:break-word
}h1{font-size:2em;margin:.67em 0
}hr{height: 0;overflow:visible
}main{display:block
}nav ol,nav ul{list-style:none
}pre{font-family:Menlo,Consolas,Roboto Mono,Ubuntu Monospace,Oxygen Mono,Liberation Mono,monospace;font-size:1em
}a{background-color:transparent
}abbr[title
]{text-decoration:underline;-webkit-text-decoration:underline dotted;text-decoration:underline dotted
}b,strong{font-weight:bolder
}code,kbd,samp{font-family:Menlo,Consolas,Roboto Mono,Ubuntu Monospace,Oxygen Mono,Liberation Mono,monospace;font-size:1em
}small{font-size: 80%
}: :-moz-selection{background-color:#b3d4fc;color:#000;text-shadow:none
}: :selection{background-color:#b3d4fc;color:#000;text-shadow:none
}audio,canvas,iframe,img,svg,video{vertical-align:middle
}audio,video{display:inline-block
}audio:not([controls
]){display:none;height: 0
}img{border-style:none
}svg{fill:currentColor
}svg:not(:root){overflow:hidden
}table{border-collapse:collapse
}button,input,select,textarea{font-family:inherit;font-size:inherit;line-height:inherit
}button,input,select{margin: 0
}button{overflow:visible;text-transform:none
}[type=button
],
[type=reset
],
[type=submit
],button{-webkit-appearance:button
}fieldset{padding:.35em .75em .625em
}input{overflow:visible
}legend{color:inherit;display:table;max-width: 100%;white-space:normal
}progress{display:inline-block;vertical-align:baseline
}select{text-transform:none
}textarea{margin: 0;overflow:auto;resize:vertical
}[type=checkbox
],
[type=radio
]{padding: 0
}[type=search
]{-webkit-appearance:textfield;outline-offset: -2px
}: :-webkit-inner-spin-button,
: :-webkit-outer-spin-button{height:auto
}: :-webkit-input-placeholder{color:inherit;opacity:.54
}: :-webkit-search-decoration{-webkit-appearance:none
}: :-webkit-file-upload-button{-webkit-appearance:button;font:inherit
}: :-moz-focus-inner{border-style:none;padding: 0
}:-moz-focusring{outline: 1px dotted ButtonText
}details,dialog{display:block
}dialog{background-color:#fff;border:solid;color:#000;height:-moz-fit-content;height:-webkit-fit-content;height:fit-content;left: 0;margin:auto;padding:1em;position:absolute;right: 0;width:-moz-fit-content;width:-webkit-fit-content;width:fit-content
}dialog:not([open
]){display:none
}summary{display:list-item
}canvas{display:inline-block
}template{display:none
}[tabindex
],a,area,button,input,label,select,summary,textarea{touch-action:manipulation
}[hidden
]{display:none
}[aria-busy=true
]{cursor:progress
}[aria-controls
]{cursor:pointer
}[aria-disabled
],
[disabled
]{cursor:not-allowed
}[aria-hidden=false
][hidden
]:not(:focus){clip:rect(0,
0,
0,
0);display:inherit;position:absolute
}.HeaderLink-module--link--2kPir{height: 100%;display:flex;align-items:center;text-decoration:none;color:inherit;padding: 0 1em;min-width:-webkit-max-content;min-width:-moz-max-content;min-width:max-content
}.HeaderLink-module--link--2kPir:visited{color:inherit
}.HeaderLink-module--link--2kPir:hover{background:#e94141
}.HeaderLink-module--link_active--14H5H{background:#c62828
}.HeaderLink-module--link_active--14H5H:hover{background:#d32b2b
}.LayoutHeader-module--header--1M4Mb{background-color:#ef5350;box-shadow: 0 2px 2px rgba(0,
0,
0,.2);position:-webkit-sticky;position:sticky;z-index: 100;top: 0;height: 3.125rem;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none
}@media (max-width:35em){.LayoutHeader-module--header--1M4Mb{height:auto
}
}@media (max-height: 25rem){.LayoutHeader-module--header--1M4Mb{position:static
}
}.LayoutHeader-module--container--3VVal{height: 100%;max-width: 72rem;margin: 0 auto;display:flex;justify-content:space-between;align-items:stretch
}.LayoutHeader-module--container--3VVal .LayoutHeader-module--homelink--2YeJ5{margin: 0;flex: 0 0;min-width:-webkit-max-content;min-width:-moz-max-content;min-width:max-content;font-size:1.5em;height: 100%;font-weight: 400
}.LayoutHeader-module--container--3VVal .LayoutHeader-module--homelink--2YeJ5 .LayoutHeader-module--link--2evP_{height: 100%;display:flex;align-items:center;color:#f3f3f3;text-decoration:none
}.LayoutHeader-module--container--3VVal .LayoutHeader-module--homelink--2YeJ5 .LayoutHeader-module--link--2evP_:visited{color:#f3f3f3
}.LayoutHeader-module--container--3VVal .LayoutHeader-module--homelink--2YeJ5 .LayoutHeader-module--link--2evP_ img{height: 3.125rem;min-width:3em;padding: 2px
}@media (max-width:35em){.LayoutHeader-module--container--3VVal .LayoutHeader-module--homelink--2YeJ5 .LayoutHeader-module--link--2evP_ .LayoutHeader-module--title---YrbU{position:absolute;opacity: 0;top: -9999px;left: -9999px
}
```
1. A list of all items in Fortnite


1. A list of all Game of Thrones Episodes.
1. A list of all songs with "Love" in the title.
1. All information about Petyr Baelish from the Game of Thrones books
1. All the movies Leonardo Dicaprio has acted in
