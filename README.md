[GET HELP WITH YOUR MACHINE LEARNING PROJECT](https://instamentor.com/mentors/leon)

# Deploy your model to Heroku

## Download this repository, then

    $ heroku create <YOUR-HEROKU-APPNAME>
    $ git push heroku master

### Now you should be able to visit the api
https://YOUR-HEROKU-APPNAME.herokuapp.com/model/api/predict/?review=beautiful%20movie

### You can visit my app:
#### https://morning-plains-31313.herokuapp.com/model/api/predict/?review=beautiful%20movie

### You can also use tool such as cURL to make a get request directly:
    $ curl 'http://morning-plains-31313.herokuapp.com/model/api/predict/?review=This%20movie%20sucks'

