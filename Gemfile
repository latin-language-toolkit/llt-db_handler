source 'https://rubygems.org'

# Specify your gem's dependencies in llt-db_handler.gemspec
gemspec
gem 'coveralls', require: false
gem 'llt-constants', git: 'git@github.com:latin-language-toolkit/llt-constants.git'
gem 'llt-form_builder', git: 'git@github.com:latin-language-toolkit/llt-form_builder.git'
gem 'llt-helpers', git: 'git@github.com:latin-language-toolkit/llt-helpers.git'

platform :ruby do
  gem 'pg', '~> 0.15'
end

platform :jruby do
  gem 'activerecord-jdbcpostgresql-adapter'
end
