1. add gem 'sidekiq' in Gemfile and then `bundle install`

2.(home directory) $mkdir app/workers

3.then create your worker file named like "hogehoge_worker.rb"

4.create `class HogehogeWorker`, and include `Sidekiq::Worker`

5.define `perform` method which has the logic you want to execute

6.run redis server

7.$bundle exec sidekiq

8.s 
