# eventmachine-sinatra-mongo-sample
Sample non-blocking web app to measure performance of Event Machine and Mongo DB with high concurrency

# Installation

gem install sinatra
gem install eventmachine
gem install em-mongo
gem install thin
gem install bson

# Start Server

ruby run.rb

# Benchmark 

ab -n 10000 -c 200 http://127.0.0.1:8181/insert
