---
title: Welcome to LA!
subtitle: Hier findest du eine Sammlung an nützlichen Infos rund um unsere Gemeinde Ladbergen.
layout: layouts/base.njk
---
<div class="responsiveImg">
  <img alt="Alte Mühle in Ladbergen" src="/images/ladbergen_alte_muehle.jpg" />
</div>

## Neu hinzugefügt:

- 27.12.2020: [Entsorgungskalender 2021](/entsorgungskalender) als Google Kalender oder direkt fürs eigene Handy als ics-Download

<!-- 
## Post pages

The pages found in in the posts

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul> -->

<!-- ## Links from an external data source

These links were sourced from [hawksworx.com](https://www.hawksworx.com/feed.json) at build time.

<ul class="listing">
{%- for item in hawksworx.entries.slice(0,5) -%}
  <li>
    <a href="{{ item.link }}">{{ item.title }}</a>
  </li>
{%- endfor -%}
</ul> -->


<!-- ## Prerequisite

- [Node and NPM](https://nodejs.org/)

## Running locally

```bash
# install the dependencies
npm install

# External data sources can be stashed locally
npm run seed

# It will then be available locally for building with
npm run start
```

## Add some Netlify helpers
Netlify Dev adds the ability to use Netlify redirects, proxies, and serverless functions.

```bash
# install the Netlify CLI in order to get Netlify Dev
npm install -g netlify-cli

# run a local server with some added Netlify sugar in front of Eleventy
netlify dev
```

A serverless functions pipeline is included via Netlify Dev. By running `netlify dev` you'll be able to execute any of your serverless functions directly like this:

- [/.netlify/functions/hello](/.netlify/functions/hello)
- [/.netlify/functions/fetch-joke](/.netlify/functions/fetch-joke)

### Redirects and proxies

Netlify's Redirects API can provide friendlier URLs as proxies to these URLs.

- [/api/hello](/api/hello)
- [/api/fetch-joke](/api/fetch-joke)

 -->


