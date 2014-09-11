# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)
require 'ci/reporter/rake/cucumber'
require 'ci/reporter/rake/rspec'

RLogin::Application.load_tasks

# ...
# Rake code that creates a task called `:rspec`
# ...

task :rspec => 'ci:setup:rspec'

# ...
# Rake code that creates a task called `:cucumber`
# ...

task :cucumber => 'ci:setup:cucumber'