desc "Adds all files then pushes to master"
task :default do
  system "git add *"
  system "git commit -a -m 'New automated blog build'"
  system "git push -u origin master"
end
