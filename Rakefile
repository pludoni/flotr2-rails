#!/usr/bin/env rake
require "bundler/gem_tasks"

desc 'upgrade to latest checkout out flotr2 version'
task :update_flotr do
  require 'fileutils'
  FileUtils.cp_r Dir.glob('flotr2/js/*'), 'vendor/assets/javascripts/flotr2-js/'

  FileUtils.cp_r Dir.glob('flotr2/lib/*'), 'vendor/assets/javascripts/flotr2-lib/'
end
