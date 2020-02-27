Here are customizations that won't be accepted by upstream.

* append ext instead of substitute for `path_for_spec`
* no-op `ensure_matching_version`
* force generating module map and umbrella header for all targets

Use:

```
Gemfile:

source 'https://rubygems.org'

gem 'cocoapods', git: 'https://github.com/shyang/CocoaPods.git', branch: '1-9-stable'
```

$ bundle install

$ bundle exec pod init ...

