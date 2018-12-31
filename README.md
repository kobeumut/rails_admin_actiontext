# RailsAdminActiontext

[![Gem Version](https://badge.fury.io/rb/rails_admin_actiontextk.svg)](http://badge.fury.io/rb/rails_admin_actiontextk)
[![Code Climate](https://codeclimate.com/github/jemcode/rails_admin_actiontextk/badges/gpa.svg)](https://codeclimate.com/github/jemcode/rails_admin_actiontextk)

[RailsAdmin](https://github.com/sferik/rails_admin) extension for enabling the Rails 6 [ActionText](https://github.com/rails/actiontext) editor.

## Installation

To enable **rails_admin_actiontext**, add the following to your `Gemfile`:

```ruby
gem 'rails_admin_actiontext'
```

It should go without saying that this plugin also requires the actiontext gem.

E.g. `gem 'actiontext'`


## Configuration
To use ActionText follow their installation instructions.

```ruby
RailsAdmin.config do |config|
  config.model Team do
    edit do
      field :description, :actiontext
    end
  end
end
```

## About Jemcode

[<img src="https://www.jemco.de/logo.svg" width="400" alt="Jemcode">][hire]

This repository is maintained and funded by Jemcode Limited. We are [available for hire][hire].

[hire]: https://www.jemco.de?utm_source=github