source :rubygems

gem "rails", "3.0.8"
gem "rack"
gem "clearance", "~> 0.11.1"
gem "sass"
gem "high_voltage"
gem "hoptoad_notifier", "~> 2.4.11"
gem "RedCloth", :require => "redcloth"
gem "paperclip"
gem "validation_reflection"
gem "formtastic"
gem "pg", "0.9.0"
gem "sqlite3"
gem "flutie", "~> 1.1.8"
gem "dynamic_form"
gem "jquery-rails"
gem "rake", "0.9.2"
gem "devise"

# RSpec needs to be in :development group to expose generators
# and rake tasks without having to type RAILS_ENV=test.
group :development, :test do
  gem "rspec-rails", "~> 2.6.1"
  gem "ruby-debug",   :platforms => :mri_18
  gem "ruby-debug19", :platforms => :mri_19
end

group :test do
  gem "cucumber-rails", "0.4.1"
  gem "factory_girl_rails"
  gem "bourne"
  gem "database_cleaner"
  gem "fakeweb"
  gem "sham_rack"
  gem "timecop"
  gem "treetop"
  gem "shoulda-matchers"
  gem "launchy"
  # gem "capybara-webkit"
  gem "thin"
end
