#!/usr/bin/env ruby

require 'rake/clean'
require 'rake/testtask'
  
task :default => [:test]

Rake::TestTask.new do |test|
  test.libs << "test"
  test.test_files = Dir["test/test_*.rb"]
end
