source 'https://rubygems.org'

gem 'rails', '3.2.2'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3-ruby', '1.2.5', :require => 'sqlite3'

#gem "heroku"
#gem 'sqlite3-ruby', '1.2.5', :group => :development
# for deployment on Heroku
gem "heroku"
group :development do
  gem 'rspec-rails', '2.0.1'

end

group :test do
gem 'rspec', '2.0.1'
gem 'webrat', '0.7.1'
end


group :production do
  gem 'pg'
  gem 'thin'
end


gem 'therubyracer'
# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

