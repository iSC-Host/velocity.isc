require "html/proofer"

task :test do
sh "bundle exec jekyll build"
HTML::Proofer.new("./assets/_site/").run
end
