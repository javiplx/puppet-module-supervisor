require 'puppetlabs_spec_helper/rake_tasks'

# https://raw.githubusercontent.com/tmtk75/ci-puppet/master/test/spec/junit.rb
require 'junit'

RSpec::Core::RakeTask.new(:test) do |t|
  t.rspec_opts = "-r junit -f JUnit -o TEST-puppet.xml"
end
