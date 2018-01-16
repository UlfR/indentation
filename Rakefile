require 'rake'

begin
  require 'jeweler'

  Jeweler::Tasks.new do |gem|
    gem.name = "indentation"
    gem.summary = "A library of extensions to Ruby's Array and String classes that allow indentation manipulation of Strings and Arrays of Strings."
    gem.description = "A library of extensions to Ruby's Array and String classes that allow indentation manipulation of Strings and Arrays of Strings."
    gem.homepage = "http://github.com/samueldana/indentation"
    gem.authors	=	["Sam Dana"]
    gem.email	=	["s.dana@prometheuscomputing.com"]
    gem.add_dependency "json"
    gem.version	=	"0.1.3"
    gem.licenses = ["MIT"]
	#s.require_paths	=	['lib']
	#s.files	=	["README.rdoc", "lib/indentation.rb", "lib/indentation/array_mod.rb", "lib/indentation/meta_info.rb", "lib/indentation/string_mod.rb", "spec/.rspec", "spec/indentation_spec.rb", "spec/spec_helper.rb"]
	#s.test_files	=	["spec/indentation_spec.rb", "spec/spec_helper.rb"]
	#s.executables	=	[]

    # gem is a Gem::Specification... see http://www.rubygems.org/read/chapter/20 for additional settings
  end
rescue LoadError => e
  puts e
  abort "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end

task :default => :build

