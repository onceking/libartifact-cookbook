source 'https://rubygems.org'

group :integration, :development, :test do
  gem 'chef-sugar'
  gem 'chef-vault'
  gem 'halite', git: 'https://github.com/poise/halite'
  gem 'poise', git: 'https://github.com/poise/poise'
end

group :lint do
  gem 'foodcritic'
  gem 'rubocop'
end

group :kitchen_common do
  gem 'test-kitchen', '~> 1.4'
end

group :kitchen_vagrant do
  gem 'kitchen-vagrant', '~> 0.17'
end

group :kitchen_cloud do
  gem 'kitchen-openstack', '~> 1.8'
end

group :unit do
  gem 'berkshelf'
  gem 'chefspec'
end

group :integration do
  gem 'serverspec'
end

group :development do
  gem 'guard'
  gem 'guard-kitchen'
  gem 'guard-rspec'
  gem 'guard-rubocop'
  gem 'rake'
end

group :doc do
  gem 'yard'
end
