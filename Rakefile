require 'rake/testtask'
require 'cane/rake_task'

Rake::TestTask.new(:test) do |t|
  t.libs << "test"
  t.test_files = FileList['test/*test.rb']
  t.verbose = true
end
