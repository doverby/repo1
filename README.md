repo1
=====

class language
  def initialize(name, creator)
    @name = name
    @creator = creator
  end
  
  def description
    puts "I'm a #{@name} created by #{@creator}!"
  end
  
  ruby = language.new("Ruby", "Yahiro Matsumoto")
  python = language.new ("Python", "Guido von Rossum")
  javascript = language.new ("Javascript", "Brendan Eich")
  
  ruby.description
  python.description
  javascript.description

