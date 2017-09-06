# LanguageTemplates

This is a ruby gem for getting templates of a language. It is based on the 
[Hello World](https://github.com/leachim6/hello-world) project.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'language_templates'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install language_templates

## Usage

LanguageTemplates has 3 primary module methods:
1. `get_template(language)` - returns the language template as a string
2. `get_languages()` - returns a list of all supported languages
3. `template_available(language)` - returns true if the given language is available

### Example:
As an example, if we want to get a template for python, we can use:


    LanguageTemplates::get_template('python')

Which will return:

    => "#!/usr/bin/env python\nprint \"Hello World\"\n"

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/ephraimrothschild/language_templates.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

