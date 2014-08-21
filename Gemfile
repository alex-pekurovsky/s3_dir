source 'https://rubygems.org'

group :test, :development do
  gem 'rake'
end

group :test do
  gem 'berkshelf',  '~> 3.1'
  gem 'chefspec',   '~> 4.0'
  gem 'foodcritic', '~> 3.0'
  gem 'rubocop',    '~> 0.23'
  gem 'coveralls'
end

group :test, :integration do
  gem 'test-kitchen',    '~> 1.2'
  gem 'kitchen-vagrant', '~> 0.14'
  gem 'kitchen-ec2',
      github: 'test-kitchen/kitchen-ec2',
      tag: 'e7f840f927518b0f9e29914205c048a463de654e'
end
