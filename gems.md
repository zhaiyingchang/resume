常用gem列表

    gem 'rails', '4.2.5'
    gem 'sass-rails', '5.0.6'
    gem 'uglifier', '>= 1.3.0'
    gem 'coffee-rails', '~> 4.0.0'
    gem 'slim'

    # frontend dependences
    gem 'bh', '~> 1.2'
    gem "font-awesome-rails"
    gem 'compass-rails'
    gem 'jquery-rails'
    gem 'select2-rails'
    gem 'bootflat-rails', '~> 0.2.1'
    gem 'jbuilder', '2.1.1'
    gem 'simple_form'
    gem 'photoswipe-rails', '~> 4.1', '>= 4.1.1'
    gem 'ionicons-rails'
    gem "active_attr"
    gem 'bootstrap-sass', '~> 3.3.6'
    gem 'x-editable-rails', github: 'yuanping/x-editable-rails'

    # backend dependences
    gem 'rest-client'
    gem 'mongoid', '~> 5.0'
    gem 'mongoid-locker'
    gem 'bson_ext'
    gem 'colorize'
    gem 'mongoid_paranoia'
    gem 'mongoid-geospatial'
    gem 'rgeo'
    gem 'hashie-forbidden_attributes'
    gem 'actionpack-action_caching'
    gem 'actionpack-page_caching'

    gem 'mailgun_rails'

    gem 'active_interaction', '~> 3.4'
    gem 'therubyracer', platforms: :ruby

    gem 'better_errors', group: :development

    group :development, :test do
      gem 'thin'
      gem 'pry-rails'
      gem 'pry-nav'
      gem "quiet_assets"
      gem 'binding_of_caller'
      gem 'rspec-rails'
      gem 'database_cleaner'
      gem 'awesome_print'
      gem 'factory_girl_rails'
      gem 'launchy'
      gem 'json_spec'
      gem 'webmock'
      gem 'capistrano'
      gem 'capistrano-rails', '~> 1.1'
      gem 'capistrano-rvm'
      gem 'capistrano-bundler'
      gem 'capistrano-passenger'
      gem 'faker'
      gem 'json-schema'
      gem 'capybara'
      gem 'letter_opener_web', '~> 1.2.0'
      gem "spring"
      gem "spring-commands-rspec"
      gem "timecop"
    end

    group :staging, :production do
      gem "dalli"
    end

    gem 'money-rails'

    #api visualization
    gem 'grape', '0.19.1'
    gem 'grape-entity' # orgnize data
    gem 'tilt-jbuilder', github: 'yuanping/tilt-jbuilder', branch: 'cache'
    gem 'grape-jbuilder'
    gem 'grape-route-helpers', '2.0.0'
    gem 'grape_logging'
    gem 'rack-cors'  #solve the CORS problem
    # gem 'swagger-ui_rails' # UI for autogenerated documentation of grape-API
    gem 'grape-swagger'
    gem 'grape-swagger-entity'
    gem 'grape-swagger-rails'

    gem 'qiniu'

    gem 'devise'

    gem 'roo' #excel parsing
    gem 'kaminari-mongoid'
    gem 'grape-kaminari', '0.1.9'#paginator gem for api
    gem 'bootstrap-kaminari-views' #bootstrap paginator UI
    gem 'rqrcode' #generate qr code
    gem 'rqrcode_png' # generate qr code in png format
    gem 'premailer-rails'
    gem 'nokogiri', '1.6.6.2'
    gem 'rchardet19' # character encoding detection library
    gem 'oga' # 解析 xml
    gem "ruby-readability", :require => 'readability'
    # gem 'ckeditor'
    gem 'mini_magick'
    gem 'enumerize'
    gem 'aasm' #state machine

    # performace optimization
    gem 'oneapm_rpm'
    gem 'airbrake', '~> 5.2'
    gem "redis", "~> 3.2"
    gem "hiredis", "~> 0.4.5"
    gem 'protobuf'

    gem 'likeable'

    gem 'sinatra', :require => nil
    gem 'sidekiq'
    gem 'sidekiq-cron'

    gem 'pili' #七牛直播服务
    gem 'dotenv-rails'
    gem 'config'
    gem 'logstash-logger'

    gem "cocoon"

    # --------- doorkeeper ------------
    gem 'doorkeeper'
    gem "doorkeeper-mongodb", github: "doorkeeper-gem/doorkeeper-mongodb"
    # --------- doorkeeper ------------

    gem "browser" # 识别浏览器

    gem 'parallel'
    gem 'ruby-progressbar'

    gem 'cancancan'

    gem 'addressable'

    # fastest JSON parser
    gem 'oj'
