# rakefile

desc 'test open'
task :build do
  sh './build.sh'
end
   
task :push do
  sh "./build.sh && git pull && git commit -am 'build' && git push"
end
