# Remote app for google presentations.

A simple remote control webapp for controlling presentation slides with your phones.

1. Go to http://murmuring-shelf-6205.herokuapp.com/ (Demo Site)
2. Put your google presentation id.
3. scan code with phone.
4. use phone to forward slide.


# Running Locally

``` bash
npm install
foreman start
```

# Running on Heroku

``` bash
heroku create
heroku labs:enable websockets
git push heroku master
heroku open
```
