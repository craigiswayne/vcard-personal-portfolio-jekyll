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
* CSS Coverage
* Filter phone number contact
* Twitter OG Tags? or maybe just OG Tags in general
* External packages to use cdns or local packages?
* SEO plugin?
* post urls ({{ post.url }})
* review list of support jekyll plugins: https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll#plugins
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
* archive pages for the following: http://127.0.0.1:4000/design/2022/02/23/best-fonts-every-designer.html
* Make sure the testimonial modal is working correctly
* Light mode / dark mode
* prefers reduced motion
* create a tool to scrape a wordpress site to jekyll
* how to absorb feed.xml

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