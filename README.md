# Decko Home Playground

Static copy of Decko's Homepage to play with color schemes.

All the css is in `site.css.scss`. It imports `scheme1.scss`. 
There is currently no better way to maintain different schemes than creationg new scheme scss files and changing the import command in
`site.css.scss`.  

## developer setup
The site is developed with [Middleman](https://middlemanapp.com). It depends on Ruby and the 
RubyGems package manager. If you don't have that you can follow these [instructions](https://middlemanapp.com/basics/install/). 
 
 
### installation 
```shell
git clone https://github.com/xithan/decko-home-playground
cd decko-home-playground
bundle install
```

### build site
```
bundle exec middleman build
```

### run local server
```
bundle exec middleman server
```  

The command returns a url where you can access the site.
Middleman automatically picks up source changes and refreshes
the site in the browser.


