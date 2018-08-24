# Installation
Set up ruby with rbenv

```
brew install rbenv
```

Install and use ruby version 2.5.1

```
rbenv install 2.5.1
rbenv local 2.5.1
```

Install bundler and jekyll

```
gem install jekyll bundler
```

Install other deps

```
bundle install
```

Build and serve

```
bundle exec jekyll serve
```