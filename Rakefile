require "bundler/gem_tasks"

# namespace :mdp do
  desc 'setup devise example migrating db and creating a default user'
  task :clean do
    ['d.txt','sss'].each{|x|
       File.delete(x);        
    }              
  end
  
  desc 'test mdpreview.rb'
  task :test do
    sh 'ruby test/mdptest.rb'
  end
  
  desc 'test mdpreview.rb'
  task :exe do
    sh 'ruby -Ilib bin/mdpreview -f sample.md'
  end
# end
