# Freezerwatch

This gem is a simple wrapper of the npm module called 'freezerwatch', available at https://github.com/apiology/freezerwatch

This is mainly useful if you have a Ruby program that needs to use freezerwatch and you don't want to package both a Gemfile and a package.json.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'freezerwatch'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install freezerwatch

## Usage

'bundle exec freezerwatch <options>'

See https://github.com/apiology/freezerwatch for more detail.

## Credits

Thanks to this post, which made this a relatively painless operation: http://mokagio.github.io/tech-journal/2015/02/25/ruby-make-a-gem-that-wraps-a-node-module.html

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To update the node module, run 'npm update freezerwatch'.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Releasing (maintainers)

Check in changes.

Update lib/freezerwatch/version.rb, bearing in mind semver.org.

git commit -m "Prepare release" lib/freezerwatch/version.rb

rake release

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/apiology/freezerwatch-gem. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

