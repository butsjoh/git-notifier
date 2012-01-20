begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|
    gemspec.name = "git-notifier"
    gemspec.summary = "Watch one or more git repositories and receive a growl notification when a change is committed"
    gemspec.description = "git-notifier is a gem for Mac Os that allows you to watch one or more git repositories and receive a growl notification when a change is committed"
    gemspec.email = "m.campana@gmail.com"
    gemspec.homepage = "http://github.com/marcocampana/git-notifier"
    gemspec.authors = ["Marco Campana"]
    gemspec.add_dependency 'daemons'
    gemspec.add_dependency 'ruby_gntp'
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end