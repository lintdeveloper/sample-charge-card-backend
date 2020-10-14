Sample Charge Card Backend
====

This is a really simple [NODE](http://www.nodejs.com/) webapp that you can use to test Paystack's sample mobile apps.

It has only 2 endpoints

- GET `/transaction/:reference` which verifies a transaction, returning the gateway response.

- POST `/transaction/initialise`which starts a new transaction with email and amount as Naira 

This is intended as a sample only: you'll likely need something more serious for your production apps.

To deploy this for free on Heroku, click this button:

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Then make your apps post to the url heroku provides e.g. jingle-bells.heroku.com.

Happy testing!
