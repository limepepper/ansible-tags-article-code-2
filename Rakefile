#
#

task default: [:test]

task lint: %i(yamllint rubocop)

desc 'Yamllint'
task :yamllint do
  puts 'Execution of Yaml linting tests'
  sh 'yamllint .'
end

desc 'Rubocop of new code'
task :rubocop do
  puts 'Execution of Rubocop linting tests'
  sh 'rubocop .'
end
