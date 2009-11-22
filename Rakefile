require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "jline"

    gem.summary = %Q{A JavaGem version of JLine - packaged by JavaGems (http://www.javagems.org)}



    gem.description = "JLine is a java library for reading and editing user input in console applications. It features tab-completion, command history, password masking, customizable keybindings, and pass-through handlers to use to chain to other console applications."    

    gem.homepage = "http://www.javagems.org/"

    gem.authors = ["Marc Prud'hommeaux - mwp1@cornell.edu"]

    gem.email = "autobuild@javagems.org"
    gem.version = "0.9.94"

  

    gem.add_development_dependency "junit", "~>3.8.1"

  end
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: sudo gem install jeweler"
end

task :default => :build
