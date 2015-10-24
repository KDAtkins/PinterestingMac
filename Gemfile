source 'https://rubygems.org'
ruby '2.2.1' #heroku spat out warning and asked to add this line in gemfile
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.4'


# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
gem 'jquery-turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'

# Add Bootstrap gem
gem 'bootstrap-sass'

# Add Devise gem
gem 'devise'

# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Paperclip is a gem that allows you to upload images
# ImageMagick must be installed and Paperclip must have access to it.
# http://cactuslab.com/imagemagick/
gem 'paperclip', '~> 4.2'

gem 'aws-sdk', '< 2.0'
gem 'masonry-rails', '0.2.0'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  # Use sqlite3 as the database for Active Record.
  # Heroku doesn't like sqlite so move it here. So use postgres for production
  gem 'sqlite3'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :production do
  # Use postgres for Heroku in prod
  gem 'pg'

  gem 'rails_12factor'
end