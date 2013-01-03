# backbone-rails

Developing javascript applications on top of rails just got faster thanks to the Rails 3.1 asset pipeline.
Like [jquery-rails](https://github.com/indirect/jquery-rails/), this gem bundles some javascript files to make them available to your application:

* [backbone](http://documentcloud.github.com/backbone)

## How to use it

### Rails 3.1

Add it to your Gemfile:

    gem 'backbone-rails'

Require backbone in `app/assets/javascripts/application.js.coffee`:

    #= require backbone-rails

With pure javascript, the line would look like `app/assets/javascripts/application.js`:

    //= require backbone-rails

## Versioning

The gem will follow backbone versioning.

## Contributors

* [John Bintz](https://github.com/johnbintz) (Support for Rails 3.0 via generators)
* [Wes Gibbs](https://github.com/wgibbs) and [Les Hill](https://github.com/leshill) (Include all dependencies as a group)
