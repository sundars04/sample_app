# Ruby on Rails Tutorial sample application

This is the sample application for Ruby on rails tutorial written by Michael Hartl

## Getting Started

To get started with the app, clone the repo and then install the needed gems:
```
$ bundle install --without production
```

Next, migrate the database:
```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:
```
$ rails test
```

If the test suite passes, you'll be ready to rung the app in a local server:
```
$ rails server
```
