twitter-data-streaming
======================

Fill up the fields in keys.api with your Twitter API
```
[API]
# Go to http://dev.twitter.com and create an app.
# The consumer key and secret will be generated for you after
consumer_key=
consumer_secret=

# After the step above, you will be redirected to your app's page.
# Create an access token under the the "Your access token" section
access_token=
access_token_secret=
```

To execute, check out ```bin/```. For example,
``` python
python ../src/stream-tweets.py "georef-tweets" "-73.817,-33.733,-28.850,16.800"
```
