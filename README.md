# vCard - Personal portfolio (for jekyll)
This for just adapts the original repo for Jekyll

Please refer to the original repo here [https://github.com/codewithsadee/vcard-personal-portfolio](https://github.com/codewithsadee/vcard-personal-portfolio)

### Debugging Liquid Template
```
<script>
    console.log('Jekyll Site values', {{ site | inspect }});
</script>
```

## Helpful links:
* [Liquid Syntax Documentation](https://shopify.github.io/liquid/)
  * [Liquid Filters](https://jekyllrb.com/docs/liquid/filters/)


### TODO:
* Testimonials need to pull from config
* Each page needs a new slug
* Css to be split across page types
* Search page?
* Collections for portfolio
* DRY... check out all code and basically prevent dry
  * Posts on blog page
  * Projects on project page
  * Filters on project page?
* CSS Coverage
* Filter phone number contact
* Twitter OG Tags? or maybe just OG Tags in general
* External packages to use cdns or local packages?
* SEO plugin?
* make use of the _data directory [https://jekyllrb.com/docs/structure/](https://jekyllrb.com/docs/structure/
* post urls ({{ post.url }})
* review list of support jekyll plugins: https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll#plugins
* 404 page
* Review all meta tags https://gist.github.com/lancejpollard/1978404
* loop through pages on navs and wherever ({{ site.html_pages | jsonify }}})
* Cypress screenshots
* Avatar Sad created with: https://readyplayer.me/hub/avatars
* Where to find site to generate avatar images
* Tracking configs
* Next up: collections for testimonials
* Light theme
* Project URLs / Individual Page
* Cheatsheet jekyll: https://gist.github.com/JJediny/a466eed62cee30ad45e2
* Should the project categories selection be a separate page? -> could remove js if it is
* move page title to default layout

### Backup:
# Installation
brew install ruby
gem install jekyll bundler
jekyll new blog-site
bundle exec jekyll serve

---

### Troubleshooting
Changing the Gemfile, requires:
```
#stop server
bundle install
jekyll serve

# or
# bundle exec jekyll serve

```

### Helpful Commands
See here for a full list: https://jekyllrb.com/docs/usage/

```
jekyll serve --config _alternative_config.yml
```

### TODO:
* create a tool to scrape a wordpress site to jekyll
* how to absorb feed.xml
* plugins to use, those that a compatible with github pages
* Debug page object
* Remove html comments and use liquid comments
* can we use liquid file types
* Fork the repo and make changes