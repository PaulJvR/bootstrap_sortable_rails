# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "bootstrap_sortable_rails"
  gem.homepage = "http://github.com/PaulJvR/bootstrap_sortable_rails"
  gem.license = "MIT"
  gem.summary = "Bootstrap-Sortable js gem"
  gem.description = "This gem adds the bootstrap-sortable.js and bootstrap-sortable.css to the asset pipeline"
  gem.email = " paul@searleconsulting.co.za"
  gem.authors = ["Paul Janse van Rensburg"]
  # dependencies defined in Gemfile
end
Jeweler::RubygemsDotOrgTasks.new


require 'rdoc/task'
Rake::RDocTask.new do |rdoc|
  version = File.exist?('VERSION') ? File.read('VERSION') : ""

  rdoc.rdoc_dir = 'rdoc'
  rdoc.title = "bootstrap_sortable_rails #{version}"
  rdoc.rdoc_files.include('README*')
  rdoc.rdoc_files.include('lib/**/*.rb')
end
