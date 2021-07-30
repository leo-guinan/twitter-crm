# Twitter CRM

This is a functioning CRM for Twitter. It will allow you to connect your Twitter account and interact with your followers.

This assumes that you have signed up for the Twitter developers program and configured an application. You will also need a MongoDB instance to work with as your datastore.

To get started, you will need to add a .env file with the following parameters:

* CONSUMER_KEY: The Twitter Consumer API Key
* CONSUMER_SECRET: The Twitter Consumer API Secret Key
* CALLBACK_URL: The Twitter callback url you configured as part of your Twitter app setup.
* MONGODB_URL: The url that points to your MongoDB database