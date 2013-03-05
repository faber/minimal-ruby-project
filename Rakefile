require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new do |t|
  t.rspec_opts = '--color'
end

task :console do
  $: << './lib'
  ARGV.clear
  require 'irb'
  IRB.start
end


task :default => :spec
