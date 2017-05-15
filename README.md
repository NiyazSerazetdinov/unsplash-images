# Unsplash images

[Build Status]
[Code Climate]
[Test Coverage]

## Description

## Additional features

## Business Requirements

## Dependencies

* PostgreSQL
* Ruby 2.3.1
* Rails 5

## Quick Start

```bash
# clone
git clone git@github.com:NiyazSerazetdinov/unsplash-images.git
cd unsplash-images

# run setup script
bin/setup

# configure ENV variables in .env
vim .env

# run server on 5000 port
bin/server
```

## Scripts

* `bin/setup` - setup required gems and migrate db if needed
* `bin/quality` - run brakeman and rails_best_practices for the app
* `bin/ci` - should be used in the CI to run specs

## Servers

[Heroku production]
