task :serve do
  sh "bundle exec jekyll serve --port5927"
end 

task :build do
  sh "bundle exec jekyll build"
end

task :bw do
  sh "bundle exec jekyll build --watch"
end 

task :deploy do
  sh "cd _site; git add .; git commit -am new-deploy; git push -u origin master"
end

task :default => :deploy do
  sh "git add .; git commit -am new-version; git push -u origin master"
end

