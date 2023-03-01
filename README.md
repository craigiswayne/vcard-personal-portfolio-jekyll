# vCard - Personal portfolio (for jekyll)
This for just adapts the original repo for Jekyll

Please refer to the original repo here [https://github.com/codewithsadee/vcard-personal-portfolio](https://github.com/codewithsadee/vcard-personal-portfolio)

### Debugging Liquid Template
```
<script>
    console.log('Jekyll Site values', {{ site | jsonify }});
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
* DRY... check out all code and basically prevent dry
  * Posts on blog page
  * Projects on project page
  * Filters on project page?
* CSS Coverage
* Filter phone number contact