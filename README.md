# europe
showcase of european countries

# Resources
- Planning: https://medium.com/@laura.ljungqvist/web-development-design-process-7c7a296228eb
- Gallery: https://gallery.io/projects/MCHbtQVoQ2HCZZkWJ_fQBCkC
- Bootstrap 4: https://getbootstrap.com/
- Stock: https://unsplash.com/
- Icons: https://fontawesome.com
- Markdown: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
- Theme: https://css-tricks.com/dark-modes-with-css/
- Accessibility: https://www.w3.org/TR/WCAG20/
- Aria: https://www.w3.org/TR/wai-aria-practices/
- Tab: https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/tabindex

### Mutuals
- [AreWeEurope](https://www.areweeurope.com/)
- [The Europeans Podcast](https://europeanspodcast.com/)
- [EU news/updates](http://www.europarl.europa.eu/news)
- [Europeana Blog](http://blog.europeana.eu/)

# Design

### Font
```
font-family: 'Raleway', sans-serif;
font-family: 'Lato', sans-serif;
```
```
<link href="https://fonts.googleapis.com/css?family=Lato:300,400,700|Raleway:300,400,700" rel="stylesheet">
```

### Media Queries
```
// Small devices (landscape phones, 576px and up)
@media (min-width: 576px) { ... }

// Medium devices (tablets, 768px and up)
@media (min-width: 768px) { ... }

// Large devices (desktops, 992px and up)
@media (min-width: 992px) { ... }

// Extra large devices (large desktops, 1200px and up)
@media (min-width: 1200px) { ... }
```

### Colors
- Primary: Orange #FFA000
- Secondary: Blue #0288D1
- Accent: Yellow #FBC02D
- Font: Black #303030
- Background: White #F5F5F5

# Development

### Files
- bootstrap.min.css (missing)
- europe-daily.css (missing)
- europe-nightly.css (missing)
- bootstrap.min.js (missing)

### information achitecture
- example.html (missing)
- index.html (missing)
- home.html (missing)
- news.html (missing)
  * article.html (missing)
- countries.html (missing)
  * country.html (missing)
- support.html (missing)
- about.html (missing)

# Elements

### Tab
```
<div tabindex="0">Tabbable due to tabindex.</div>
```

### Image
```
<img src="(link)" alt="(description)" title="(img title)" aria-labelledby=""> <p id="(text about the image)"></p>
```
```
<img src="" alt="" title="" aria-labelledby=""> <p id=""></p>
```

# TODO

### TODO: Brief and Deliverables
- turn sketches into wireframe
  * upload to gallery
- turn wireframe into mockup
  * upload to gallery

### TODO: CSS
- decide between [lightsoff](https://designshack.net/articles/css/lightsoff/) or [prefers-color-scheme](https://css-tricks.com/dark-modes-with-css/) for theme toggle
- create initial theme differences in css to an element, add a theme toggle and test https://css-tricks.com/dark-modes-with-css/

### TODO: HTML
- meta 
- index
- home
  * album (https://getbootstrap.com/docs/4.3/examples/album/)
- navigation (see sketches)
  * 100% x 100%
- news
  * album (https://getbootstrap.com/docs/4.3/examples/blog/)
- all countries (https://getbootstrap.com/docs/4.3/examples/product/)
  * 49 individual countries (see sketches)
- support
- about

### TODO: JS 
- ...
