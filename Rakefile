namespace :test do
  
  task :all do
    Rake::Task['test:spec'].invoke
    Rake::Task['test:cucumber'].invoke
  end

  task :spec do
    sh 'rspec'
  end

  task :cucumber do
    sh 'cucumber'
  end
end
