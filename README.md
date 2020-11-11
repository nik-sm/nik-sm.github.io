[![Build Status](https://travis-ci.com/nik-sm/nik-sm.github.io.svg?branch=master)](https://travis-ci.com/nik-sm/nik-sm.github.io)

# Setup

First, install `rbenv` and `ruby-build`. (See [dotfiles](https://github.com/nik-sm/dotfiles) for example)

```bash
rbenv install 2.7.2
gem install jekyll bundler
bundle install
```

# Editing
- Note that after certain changes (especially to `_config.yml`), one must `rm -rf _site/` because jekyll's caching logic will otherwise not detect the change.
