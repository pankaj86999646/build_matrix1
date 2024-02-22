require 'rubygems/package_task'

# Define a new Gem::PackageTask
Gem::PackageTask.new(Gem::Specification.load('new.gemspec')) do |pkg|
  pkg.need_tar = true   # Set to true if you want to create a .tar.gz file
  pkg.need_zip = true   # Set to true if you want to create a .zip file
end
task :test do
  # Add your test commands here
end

