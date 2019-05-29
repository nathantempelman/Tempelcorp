# Tempelcorp

Why *wouldn't* you make a basic static website in rails?


## For when I blow away the repo and forget how to start it up again

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the likely nonexistant database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that the tests I haven't written aren't running correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails s(erver)
```


