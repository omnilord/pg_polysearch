# PgPolysearch

A search gem providing the ability to search across numerous ActiveRecord models by field and return them in one query.

## Status

Currently a *work in progress* on my local machine.  I have a private project from which I am extracting the functional artifacts for this gem.  Once I migrate that personal project locally to the gem and have it work, I will be pushing everything here.  If you are interested in helping, I will probably need someone to spitball with regarding how to test this code since it is explicitly dependent on Postgres extensions.

## Installation

### Pre-Requisites

* Rails 5.0+
* PostgreSQL

### Instructions

Add this line to your application's Gemfile:

```ruby
gem 'pg_polysearch'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install pg_polysearch

## Usage

TODO: Write usage instructions here

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/omnilord/pg_polysearch. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the PgPolysearch project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/omnilord/pg_polysearch/blob/master/CODE_OF_CONDUCT.md).
