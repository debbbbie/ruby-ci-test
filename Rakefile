require 'rake'
# require 'bundler/gem_tasks'
require 'rspec/core/rake_task'

task "default" => "ci"

desc "Run all tests for CI"
task "ci" => "spec"
RSpec::Core::RakeTask.new(:spec)
