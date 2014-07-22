source 'http://rubygems.org'

gem 'rails', '3.2.19'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'#, '3.1.6'
  gem 'coffee-rails'#, '3.1.1'
  gem 'uglifier'#, '1.0.3'


  # gem 'sass-rails',  '~> 3.2.3'
  # gem 'coffee-rails', '~> 3.2.1'
  # gem 'uglifier', '>= 1.0.3'
end

gem 'activemerchant', '~> 1.43.1'
gem 'activemerchant_paybox_direct_plus', '~> 0.2.0'

#gem 'jquery-rails'
gem 'jquery-rails', '1.0.19'

#gem 'mysql2', '>= 0.3'
gem 'mysql2', '0.3.11'

 #gem 'thinking-sphinx', #'2.0.3'
   #:git     => 'git://github.com/freelancing-god/thinking-sphinx.git',
#   #:branch  => 'rails3',
   #:require => 'thinking_sphinx'
 gem 'thinking-sphinx', '2.0.14'

 #Zendesk API
 gem "zendesk_api"

 # Vérification via l'algo de Luhn
 gem "luhn"

 # gem 'paperclip', '3.1.4', :git => 'git://github.com/thoughtbot/paperclip.git', :branch => 'v3.1'
 gem 'paperclip', :git => 'git://github.com/thoughtbot/paperclip.git', :branch => 'v3.2'

 #gem 'will_paginate'#, '3'
 gem 'will_paginate', '3.0.7'

 #gem "friendly_id", "~> 4.0.0"
 gem 'friendly_id', "4.0.10.1"

 #gem 'simple_form'
 gem 'simple_form', '2.0.2'
 
 # gem 'devise', '1.4.9'
 gem 'devise', '2.2.8'
 gem 'devise-encryptable'

 # Solve UTF8 problem
 gem 'utf8-cleaner'

 #gem 'ts-delayed-delta',  :require => 'thinking_sphinx/deltas/delayed_delta'
 gem 'ts-delayed-delta', '1.1.3', :require => 'thinking_sphinx/deltas/delayed_delta'

 #gem 'engineyard'
 # gem 'engineyard', '1.4.29'
 
 #gem "daemons"#, "<= 1.0.10"
 gem 'daemons', '1.1.9'

 #gem 'acts_as_list'
 gem 'acts_as_list', '0.4.0'

 #gem 'inherited_resources'
 gem 'inherited_resources', '1.3.1'

# gem 'inherited_resources_views'
 #gem 'simple-navigation'
 gem 'simple-navigation', '3.7.0'

 gem 'cancan', '1.6.10'

 #gem 'haml'
 gem 'haml', '3.1.6'

 #gem 'sass'
 gem 'sass', '3.1.20'

 #gem 'meta_search' , :git => "git://github.com/ernie/meta_search.git"
 gem 'meta_search', '1.1.3' , :git => "git://github.com/ernie/meta_search.git"

 #gem 'geo_ip'
 gem 'geo_ip', '0.5.0'

 gem "state_machine" , "0.9.4"
 #gem 'delayed_job'
 #gem 'delayed_job_active_record'
 gem 'delayed_job_active_record', '0.3.2'

 #gem 'ssl_requirement'
 #gem 'paypal-express', '0.4.2'
 gem 'paypal-express', '0.5.5'

 #gem 'exception_notification'
 gem 'exception_notification', '2.6.1'

 gem 'unicorn', '4.3.1', :group => :staging

#gem 'sitemap_generator'
gem 'sitemap_generator', '3.1.1'

# User Agent parser gem / Remove from vendor included as gem
gem 'useragent', '~> 0.10.0'

# Cron tab - Non utilisé
#gem 'whenever', :require => false
# gem 'whenever', '0.7.3', :require => false

#group :staging, :production do
  #gem 'execjs'
	gem 'execjs', '1.4.0'


  gem 'therubyracer', '0.12.1'
	#gem 'therubyracer', '0.10.1'
#end

# Retours de Mandrill
gem 'mandrill-rails'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
# group :development, :test do
#   gem 'webrat'
# end
# gem 'mocha', '0.12.0', :group => :test

# Gestion des mails responsive
gem 'roadie', '2.4.3'
# gem 'premailer-rails'
# gem 'nokogiri'
# gem 'hpricot'

group :development do
  gem 'jazz_hands'
  gem "awesome_print"
  gem "letter_opener"
  gem 'capistrano', '~> 2.15'

  gem 'binding_of_caller', :platforms=>[:mri_21]
  gem 'guard-bundler'
  gem 'guard-rails'
  gem 'guard-rspec'
  gem 'terminal-notifier-guard'
  gem 'quiet_assets'

end

group :development, :test do
  gem 'factory_girl_rails'
  # gem 'rspec'
  gem 'rspec-rails'
  #gem 'rspec-collection_matchers', '~> 0.0.3'
end

group :test do
  gem "faker"#, "~> 1.1.2"
  gem "capybara"#, "~> 2.1.0"
  gem "database_cleaner"#, "~> 1.0.1"
  gem "launchy"#, "~> 2.3.0 »

end







