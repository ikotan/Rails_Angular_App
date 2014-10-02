== README
 
This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

Please feel free to use a different markup language if you do not plan to run
<tt>rake doc:app</tt>.

### setup info

* rails setup

```
$ bundle exec rails new rails_angular_app --skip-bundle -T
```

```
$ cd rails_angular_app
$ git init
```

```
$ cd rails_angular_app
$ bundle install --path vendor/bundle
```

```
$ cd rails_angular_app
$ bundle exec spring binstub --all
```

* angular setup

```
$ cd rails_angular_app
$ mkdir front
$ cd front
$ yo angular --coffee --minsafe
```

```
$ npm install
$ bower install
```

```
$ cd rails_angular_app/front
$ grunt serve
```

```
$ grunt build
```

### release info

* releases/1.0.0


