forked from sausheong/chirp
=====

Simple Sinatra-based micro-blog/Twitter clone

To run the app, get the code. Then go to the models.rb file and change the database URL accordingly. After that, go to irb, require the models file, and run this:

> DataMapper.auto_migrate!
This will create the necessary database. Then in the directory, run this

> ruby chirp.rb
Go to http://localhost:4567 and you’re up and running locally! Of course, you need to register your RPX account and then change login.erb accordingly.
