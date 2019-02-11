## How to use (MAC OSX)
"Remote theme method" case

#### Install bundler
- brew install ruby
- (sudo) gem install bundler

#### Set Configs
- bundler init
- Modify Gemfile
```
source "https://rubygems.org"

gem "jekyll-include-cache"
gem "github-pages", group: :jekyll_plugins
```
- bundler install

#### Modify _config.yml
- get _config.yml from [https://github.com/mmistakes/minimal-mistakes](https://github.com/mmistakes/minimal-mistakes)
- set index.html
```

---
layout: home
author_profile: true
---
```
- modify _config.yml
```
remote_theme             : "mmistakes/minimal-mistakes"
locale                   : "en-US" # Your locale
name                     : "Your Name"
description              : "Description"
url                      : "https://yourname.github.io"
```

#### Run
- bundle exec jekyll serve

#### Testpage
- [Go to local page](http://localhost:4000)

#### Added posts
- Add files to "_posts" folder :: [Sample](https://github.com/mmistakes/minimal-mistakes/tree/master/test/_posts)
