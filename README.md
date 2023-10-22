# vCard - Personal portfolio (for jekyll)
This for just adapts the original repo for Jekyll

Please refer to the original repo here [https://github.com/codewithsadee/vcard-personal-portfolio](https://github.com/codewithsadee/vcard-personal-portfolio)

## Getting Started
Start the server
```shell
bundle exec jekyll serve
```

## Avatar / Emoji / Memoji
You can find the collection here: https://www.figma.com/community/file/913339145625776252

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
* try see if you can set custom paths for files in the config file
* custom filter for jekyll, do it on the phone number
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
* [review list of support jekyll plugins](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll#plugins)
* Review all meta tags https://gist.github.com/lancejpollard/1978404
* loop through pages on navs and wherever ({{ site.html_pages | jsonify }}})
* Cypress screenshots
* Avatar Sad created with: https://readyplayer.me/hub/avatars
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
* remove need for active classes
* sass mixing for media queries
* css for pages
* css code coverage
* js code coverage
* css palette
* pwa tests
* github tags for the following: jekyll-theme jekyll-template responsive-web-design pwa jamstack
* checkout chirpy theme `jekyll-theme-chipry`
* maybe a new repo called `jekyll-theme-vcard-personal-portfolio`
* search function, checkout chirpy
* checkout all the settings from the chirpy repo
* dockerfile that contains all the ruby shit?
* code snippets using what chirpy does, love the copy command
* dala pwa
* themes for notable periods in the year and use js to load the stylesheets
  * default stylesheet is grayscale?
  * and js loads just the variables?
  * halloween?
* archives, taken from: https://github.com/mmistakes/minimal-mistakes/blob/master/_config.yml
```
  # Archives
#  Type
#  - GitHub Pages compatible archive pages built with Liquid ~> type: liquid (default)
#  - Jekyll Archives plugin archive pages ~> type: jekyll-archives
#  Path (examples)
#  - Archive page should exist at path when using Liquid method or you can
#    expect broken links (especially with breadcrumbs enabled)
#  - <base_path>/tags/my-awesome-tag/index.html ~> path: /tags/
#  - <base_path>/categories/my-awesome-category/index.html ~> path: /categories/
#  - <base_path>/my-awesome-category/index.html ~> path: /
category_archive:
type: liquid
path: /categories/
tag_archive:
type: liquid
path: /tags/
```

### Backup:
# Installation
brew install ruby
gem install jekyll bundler
jekyll new blog-site
bundle exec jekyll serve

### Installs Plugins
Update the `Gemfile` section where plugins are listed
```
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
end
```

Then run `bundle update`

---

### Troubleshooting
After making changes to the Gemfile, stop the server and...
```
bundle install
bundle exec jekyll serve
```

### Helpful Commands
See here for a full list: https://jekyllrb.com/docs/usage/

```
jekyll serve --config _alternative_config.yml
```
