### This repo is now deprecated. The gem source code now resides here: [https://github.com/kyleshevlin/shevy](https://github.com/kyleshevlin/shevy).

# Shevy

Shevy is a small Sass library for simple, configurable typography with perfect vertical rhythm.

This is Shevy in gem form. If you are looking for the original repo, go to [https://github.com/kyleshevlin/shevy](https://github.com/kyleshevlin/shevy).

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'shevy'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install shevy

### Important

After the gem is installed, you will need to add Shevy to your `application.css` file.

```
*= require shevy
```

Add this _before_ your other stylesheets. Lastly, import it into your Sass files:

```sass
@import 'shevy';
```

## Usage

Usage can be found at [https://github.com/kyleshevlin/shevy](https://github.com/kyleshevlin/shevy).

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/kyleshevlin/shevy-gem.

