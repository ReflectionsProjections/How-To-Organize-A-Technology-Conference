# SEO (Seach Engine Optimization)
A guide on how to configure meta tags for SEO.

## Open Graph Protocal
Setting these meta tags will configure how the website preview will look on social media when shared. Examples of where this shows up includes Facebook posts and Facebook Messenger

Here's a basic example which is the bare minimum that needs to be setup for the the RP Site:
```
<meta property="og:title" content="Reflections Projections" />
<meta property="og:type" content="website" />
<meta property="og:url" content="http://reflectionsprojections.org" />
<meta property="og:image" content="http://acmrp.org/static/someimage.png" />
```
*Media specific tags also exist for video and music

### More Information
[Facebook Webmasters Guidelines](https://developers.facebook.com/docs/sharing/webmasters/)  
[The Open Graph Protocal Website](http://ogp.me/)  

## Twitter Cards
Twitter has a their own meta tags for website previews known as "Twitter Cards".

Here's a basic example:
```
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:site" content="@uiuc_rp">
<meta name="twitter:creator" content="@uiuc_rp">
<meta name="twitter:title" content="Reflections Projections 2019 Website">
<meta name="twitter:description" content="Reflections | Projections is an annual technology conference held at the University of Illinois at Urbana-Champaign. Inviting premier speakers, influencers, and companies, it features a puzzle competition, speaker events, and a 24 hour AI hackathon. Reflections | Projections is coming on its 25th anniversary this year, upholding its standards of excellence.">
<meta name="twitter:image" content="http://acmrp.org/static/someimage.png">
```

### More Information
[Twitter Cards Documentation](https://developer.twitter.com/en/docs/tweets/optimize-with-cards/overview/abouts-cards)

## Libraries to Help
### NextJS
[NextJS Head Component Documentation](https://nextjs.org/docs#populating-head)

### React Helmet
"A document head manager for React"  
[React Helmet Github Repository](https://github.com/nfl/react-helmet)
