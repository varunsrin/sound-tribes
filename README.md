sound-tribes
================

# README

### How do I run the server?

* Install RVM, correct Ruby (`curl -sSL https://get.rvm.io | bash -s stable --ruby`)
* Run **bundle install**
* If fails at PostGreSQL:
  * Download app from postgresapp.com and install
  * gem install pg -- --with-pg-config=/Applications/Postgres.app/Contents/Versions/9.3/bin/pg_config
* Run `figaro install`
* Add environment variables for services to application.yml
* Run rails server
* Go to http://localhost:3000/ on your browser


### How do I complete a test pass?

* Run 'rspec'
