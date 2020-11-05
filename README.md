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

## Specially for React

### - React Helmet 
https://www.npmjs.com/package/react-helmet
