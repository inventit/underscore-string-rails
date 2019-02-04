# Underscore::String::Rails

[underscore.string](https://github.com/epeli/underscore.string) for Rails.

## Installation

`underscore-string-rails` depends on [underscore-rails](https://github.com/rweng/underscore-rails).

So Add these lines to your application's Gemfile:

```ruby
gem 'underscore-rails'
gem 'underscore-string-rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install underscore-rails underscore-string-rails

## Usage

In your `application.js` you will need to add these lines:

    //= require underscore
    //= require underscore.string

And mixin `underscore.string` to `underscore` after document is ready to make all exported underscore.string functions via '_'.

```javascript
$(function() {
  _.mixin s.exports()
}
```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/inventit/underscore-string-rails.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
