# frozen_string_literal: true

require 'rake/testtask'

desc 'Run tests'
task default: :test

Rake::TestTask.new(:test) do |t|
  t.libs << 'test'
  t.libs << 'lib'
  t.test_files = FileList['test/**/*_test.rb']
end
