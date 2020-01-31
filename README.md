# Script Parser

> This is a Rails 5 project template for cloning and starting a quick project.

## Built With
 
 - Ruby
 - Rails
 
## Getting Started

To get a local copy up and running follow these simple example steps.


## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

```
$ bundle update
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

## Create Heroku
```
$ git push
```

```
$ heroku create
```

```
$ git push heroku master
```

If migrations,
```
$ heroku run rails db:migrate
```

If problems,

```
$ heroku logs
```
