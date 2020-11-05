## Let's work on SEO

<hr/>

### - Just-in-time Preloading
Hover while something is visible or even when something is hovered.
```
<script src="//instant.page/5.1.0" type="module" integrity="sha384-by67kQnR+pyfy8yWP4kPO12fHKRLHZPfEsiSXR8u2IKcTdxD805MGUXBzVPnkLHw"></script>
<br/>
```

```
< link rel="preload"/>
< link rel="preload" href="style.css" as="style">
< link rel="preload" href="main.js" as="script">
```
Read More: 
https://developer.mozilla.org/en-US/docs/Web/HTML/Preloading_content
<br/>
https://instant.page/
<hr/>

### - Google Search console

<hr/>

### - XML Sitemap
https://www.xml-sitemaps.com/

<hr/>

### - Web App Manifest (manifest.json)
https://web.dev/add-manifest/

<hr/>

### - Lighthouse
https://developers.google.com/web/tools/lighthouse/
https://developers.google.com/speed/pagespeed/insights/

<hr/>

### Robots.txt
```
#Rule 1
User-agent: Googlebot
Disallow:

#Rule2
User-agent: Bingbot
Disallow:

Sitemap: https://abc.com/sitemap.xml
```

<hr/>

### - Schema.org
https://schema.org/docs/gs.html

<hr/>

### Mobile Friendly Test
https://search.google.com/test/mobile-friendly?view=fetch-info&id=1a8fsE-phsiwXGWOKKPPpw

<hr/>

### - Cache control

<hr/>

### - Compress Resources

<hr/>

### - Google Ads

<hr/>

### - Google Analytics

<hr/>

### - Object to Json
data={"name":"Anant"}
to render, data is first loaded, parsed,comiled and executed by Javascript engine
How to solve?
1. SSR
2. data = JSON.parse('{"name": "Anant"}') - faster (only one token, less checks, around 2x fast)

Don't do it by hand, Using Webpack or babel plugins - <br/>
https://github.com/nd-02110114/babel-plugin-object-to-json-parse

<hr/>

### In head 
```
<meta charset="utf-8">
    <link rel="manifest" href="/manifest.json">
    <meta http-equiv="Cache-control" content="max-age=31536000">
    <meta name="google-signin-client_id"
        content="984030785264-j712abraevpq0shjrp009t2v2l1hggqc.apps.googleusercontent.com">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description"
        content="Looking for the best web designers, Developers and mobile app developers to take care of your small business or e-commerce site? You’ve come to the right place! PINKFRY helps you launching a fruitful online presence and also takes care of your continuous escalation in the online market. " />
    <meta name="keywords"
        content="pinkfry, build your website, create your own website,build apps, shopify, wordpress , aws , pink fry, Web Development Company, Mobile Development, Online Business, Google My Business, SEO" />
    <meta name="robots" content="index, follow" />
    <meta name="googlebot" content="index, follow" />
    <meta property="og:image" content="https://www.pinkfry.tech/images/pinkfry_one.webp" />
    <meta property="og:description"
        content="PINKFRY helps you launching a fruitful online presence and also takes care of your continuous escalation in the online market." />
    <meta property="og:url" content="https://www.pinkfry.tech" />

    <meta http-equiv="Content-Security-Policy" content="upgrade-insecure-requests">

    <!-- Chrome, Firefox OS and Opera -->
    <meta name="theme-color" content="#00d747">
    <!-- Windows Phone -->
    <meta name="msapplication-navbutton-color" content="#00d747">
    <!-- iOS Safari -->
    <meta name="apple-mobile-web-app-status-bar-style" content="#00d747">

    <!-- Favicon -->
    <link rel="icon" type="image/webp" sizes="56x56" href="images/pinkfry.webp">
  ```
    
## Specially for React

### - React Helmet 
https://www.npmjs.com/package/react-helmet
