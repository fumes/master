## What?_Fumes is an online photography magazine broadcasting human interest stories mainly from south east asia._ _Fumes project was started by two photographers. A metaphor to play with, delivering ideas via images._
♡ Fumes website is now refactored.  ☯ Articles are structured as `photographer`|`curator` symbiotic work.  ✿ This hopefully will bloom greener fumes soon...## StructureLooks like this is the only option, for now:
- Compiled jekyll **_site** (yup, we still need plugins here..) in [Master branch](https://github.com/fumes/fumes.github.io/tree/master) - Real **jekyll master** live in the [Source branch](https://github.com/fumes/fumes.github.io/tree/source)- More **working branches** maybe present at times...## To do##### Urgent:- UX tests
- speed-up Jekyll Regeneration (w/ gulp | jekyll -pre?)
- open graph tests- check domain pointer (cname stuff)- twitter account- twitter cards tests- improve [liquid design](https://github.com/Shopify/liquid/wiki/Liquid-for-Designers) and [liquid programming](https://github.com/Shopify/liquid/wiki/Liquid-for-Programmers) skills
- figure out [github](https://help.github.com/) ##### Sometime soon:- automatic rake publish script- chrome web app- improve + maybe move gulp tasks up the tree- use authors.yml##### One day:- https and install service workers
- diquss
- print.css
- mailchimp## Fumes Website Features   ✓ serious [responsive](https://github.com/wildlyinaccurate/jekyll-responsive-image) [image](https://github.com/BBC-News/Imager.js/).  ✓ ultra simple [codepen-nerd](http://codepen.io/rokma/full/pJBXbg/) responsive logo.  ✓ smart [inline svg icons](https://github.com/eduardoboucas/eduardoboucas.github.io/tree/master/_includes/svg).  ✓ auto [tag](http://geoexamples.com/other/2015/06/04/Jekyll-tags-plugin-gh-pages.html) navigation.  ✓ auto [category](http://geoexamples.com/other/2015/06/04/Jekyll-tags-plugin-gh-pages.html) navigation.  ✓ Post thumbs. Front-matter declared.  ✓ open graph  ✓ handy prev-next articles navigation.
✘ No plugins dependencies.  ✘ print.css.  ✘ twitter [cards](https://github.com/merlos/jekyll-auto-image#example-using-twitter-cards)  ✘ disqus comments.  ✘ twitter account and cards setup.  ✘ [google authors](http://milanaryal.com/2015/integrating-social-meta-tags-into-jekyll/#integrating-google-authorship-into-jekyll)  ✘ [Google Author Rich Snippets](http://davidensinger.com/2013/05/setting-up-google-author-rich-snippets/)  ✘ service workers.

## Fumes Production Technologies 
Jekyll, Git, Github pages, Sass, Ruby, Nmp, Gulp, Bundler, Normalize, svgs, plus various code clips & techniques taken here and there...  

## Getting Started

#### 1. Install gulp globally, at your terminal prompt:
```sh
npm install --global gulp
```

#### 2. Install gulp in project local dir:
```sh
npm install --save-dev gulp
```

#### 3. Run gulp:
```sh
gulp
```
The default task will take care of Sass and BrowserSync.
Your run this on his own terminal window.

#### 4. Get started with bundler. Install it globally! 
```sh
gem install bundler```

#### 5. Install gems in project local dir:
```sh
bundle install
```
## Gems dependencies:
- github-pages
- rmagick
- jekyll-sitemap
- [jekyll-responsive_image](https://github.com/wildlyinaccurate/jekyll-responsive-image)- [jekyll-video-tag](https://github.com/danbee/jekyll-video-tag ) ## Plugins dependencies:
- [categories_generator.rb](http://geoexamples.com/other/2015/06/04/Jekyll-tags-plugin-gh-pages.html)
- [tags_generator.rb](http://geoexamples.com/other/2015/06/04/Jekyll-tags-plugin-gh-pages.html)
- [responsive_image.rb](https://github.com/wildlyinaccurate/jekyll-responsive-image)
- [imager.js](https://github.com/BBC-News/Imager.js/)## More credits- [github setup tips](http://ixti.net/software/2013/01/28/using-jekyll-plugins-on-github-pages.html)## Photo rightsAll photos © the authors. All photos rights reserved.  
Except as indicated on a per article basis. Some photos articles are released under CC-BY Creative Commons license. Some other ones are CC0. Everything else is GPL.