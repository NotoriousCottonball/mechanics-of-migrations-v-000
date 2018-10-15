require_relative './config/environment'
require 'sinatra/activerecord/rake'

task :console do
  def reload! 
    load_all 'Rakefile'
  end
  ARGV.clear
  Pry.start
end

