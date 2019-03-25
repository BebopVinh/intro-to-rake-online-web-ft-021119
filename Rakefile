namespace :greeting do
  desc 'outputs hello to the terminal'
  task :hello do
    puts "Hello from Rake!"
  end

  desc 'outputs hola to the terminal'
  task :hola do
    puts "Hola de Rake!"
  end
end

namespace :db do
  desc 'migrate changes to your database'
  task :migrate => :environment do
    Student.create_table
  end
end
