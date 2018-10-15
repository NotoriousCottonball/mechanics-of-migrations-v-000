require_relative './config/environment'
require 'sinatra/activerecord/rake'

task :console do
  def reload!
    load 'db/migrate'
  end
  ARGV.clear
  Pry.start
end

