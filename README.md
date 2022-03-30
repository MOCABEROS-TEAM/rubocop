# Ruby & Rails Style Guides

### Usage
Add a git submodule
```shell
$ git submodule add https://github.com/mocaberos/rubocop.git ./vendor/rubocop
```
Inherit settings
```yaml
# For Rails
inherit_from: ./vendor/rubocop/rails.rubocop.yml
```
```yaml
# For Ruby
inherit_from: ./vendor/rubocop/ruby.rubocop.yml
```

### reference
- https://github.com/cookpad/global-style-guides
- https://github.com/rubocop/ruby-style-guide
- https://github.com/rubocop/rails-style-guide
