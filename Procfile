web:  bundle exec thin start -p $PORT
faye: bundle exec rackup faye.ru -s thin -p $PORT -E production
db:   mongod run --config /usr/local/Cellar/mongodb/1.8.3-x86_64/mongod.conf
