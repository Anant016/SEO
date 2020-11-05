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

### - XML Sitemap
https://www.xml-sitemaps.com/

### - Web App Manifest (manifest.json)
https://web.dev/add-manifest/

### - Lighthouse
https://developers.google.com/web/tools/lighthouse/

### - Schema.org
https://schema.org/docs/gs.html

### - Cache control

### - Compress Resources

### - Google Ads

### - Google Analytics

### -
data={"name":"Anant"}
to render, data is first loaded, parsed,comiled and executed by Javascript engine
How to solve?
1. SSR
2. data = JSON.parse('{"name": "Anant"}') - faster (only one token, less checks, around 2x fast)

Don't do it by hand, Using Webpack or babel plugins

## Specially for React

### - React Helmet 
https://www.npmjs.com/package/react-helmet
