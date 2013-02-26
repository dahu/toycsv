task 'lib/mycsv/parser.rb' => ['lib/mycsv/parser.racc'] do |t|
	sh "racc -o lib/mycsv/parser.rb lib/mycsv/parser.racc"
end

task :default => 'lib/mycsv/parser.rb'
