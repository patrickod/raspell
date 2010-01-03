
require 'rubygems'
gem 'echoe', '>=2.3'
require 'echoe'

Echoe.new("raspell") do |p|
  p.description = p.summary = "A fork of raspell for ruby 1.9.1"
  p.url = "http://github.com/patrickod/raspell"  
  p.docs_host = "blog.evanweaver.com:~/www/bax/public/files/doc/"
  p.has_rdoc = false # avoids warnings on gem install
  p.rdoc_pattern = /CHANGELOG|EXAMPLE|LICENSE|README|lib/
  p.rdoc_options = [] # don't want to include the stubbed out source
  p.require_signed = true
  p.name = "raspell"
  p.author = "Patrick O'Doherty"
end
