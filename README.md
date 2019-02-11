# How to use (MAC OSX)
"Gem-based method" case

#### Install bundler
(sudo) gem install bundler

#### Set Configs
bundler init

Modify Gemfile
```
source "https://rubygems.org"

gem "jekyll"
gem "minimal-mistakes-jekyll"

group :jekyll_plugins do
end
```

bundler install

Modify _config.yml

#### Run
bundle exec jekyll serve

#### Testpage
[LINK](http://localhost:4000)