task :console do 
  Pry.start
end

task :environment do
  require_relative './config/environment'
end

namespace :db do 
  task migrate: :environment do
    Student.create_table
  end

  task seed: :environment do
    require_relative './db/seeds'
  end
end

namespace :greeting do 
task :hello do
  puts "hello from Rake!"
end

task :hola do 
  puts "hola de Rake!"
end 



end 
