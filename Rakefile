# frozen_string_literal: true

require 'rake/testtask'

Rake::TestTask.new(:test) do |test|
  test.libs << 'lib' << 'test'
  test.pattern = 'test/test.rb'
  test.verbose = true
end

task default: :test
