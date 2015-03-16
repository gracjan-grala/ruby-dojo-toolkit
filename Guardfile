guard :rspec, cmd: 'rspec' do
  watch('spec/spec_helper.rb') { 'spec' }
  watch(%r{^app/(.+)\.rb$})    { |m| "spec/#{m[1]}_spec.rb" }
  watch(%r{^spec/(.+)\.rb$})
end

