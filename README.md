# Table Of Contents
* [meta tags](#metatags)

## meta tags
A meta tag is an HTML tag that provides information about a page to search engines and users. 
```html
<!-- MS, fb & Whatsapp -->

<!-- MS Tile - for Microsoft apps-->
<meta name="msapplication-TileImage" content="http://www.example.com/image01.jpg">    

<!-- fb & Whatsapp -->

<!-- Site Name, Title, and Description to be displayed -->
<meta property="og:site_name" content="The Rock Photo Studio">
<meta property="og:title" content="The Rock Photo Studio in Florida">
<meta property="og:description" content="The best photo studio for your events">

<!-- Image to display -->
<!-- Replace   «example.com/image01.jpg» with your own -->
<meta property="og:image" content="http://www.example.com/image01.jpg">

<!-- No need to change anything here -->
<meta property="og:type" content="website" />
<meta property="og:image:type" content="image/jpeg">

<!-- Size of image. Any size up to 300. Anything above 300px will not work in WhatsApp -->
<meta property="og:image:width" content="300">
<meta property="og:image:height" content="300">

<!-- Website to visit when clicked in fb or WhatsApp-->
<meta property="og:url" content="http://www.example.com">
```
