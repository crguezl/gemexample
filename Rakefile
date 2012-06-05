# http://railscasts.com/episodes/135-making-a-gem
require "rubygems"
require "rake"
require "echoe"

Echoe.new('uniquify', '0.1.0') do |p|
  p.description = "Generate a unique token with Active Record."
  p.url         = "http://github.com/crguezl/uniquify"
  p.author      = "Casiano Rodriguez-Leon"
  p.email       = "crguezl@ull.edu.es"
  p.ignore_pattern = ["tmp/*", "script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }
