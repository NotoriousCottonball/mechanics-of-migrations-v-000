require_relative './config/environment'
require 'sinatra/activerecord/rake'

task :console do
  def reload!
    load './db/migrate/01_create_artists.rb'
  end
  ARGV.clear
  Pry.start
end

