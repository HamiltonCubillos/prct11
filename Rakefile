require "bundler/gem_tasks"
require 'rake/testtask' 
require 'rdoc/task'

$:.unshift File.dirname(__FILE__) + 'lib'
$:.unshift './lib', './spec'

require 'rspec/core/rake_task'
RSpec::Core::RakeTask.new
task :default => :spec

Rake::RDocTask.new do |rd|
    rd.main = "README.md"
    rd.rdoc_files.include("README.md", "lib/**/*.rb")
<<<<<<< HEAD
end


=======
  end
>>>>>>> 3d3eb21a3a63c9bfaf6b4d1c985a9fb32b1b3c66
