#!/usr/bin/env rake
require "bundler/gem_tasks"

#source: http://www.ruby-doc.org/stdlib-1.9.3/libdoc/rubygems/rdoc/Gem/PackageTask.html
require 'rubygems/package_task'
spec = eval(File.read('rsocialize.gemspec'))
Gem::PackageTask.new(spec) do |pkg|
end
