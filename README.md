# AzizYelpCamp

YelpCamp is a project that was completed as a part of [Colt Steele's bootcamp](https://www.udemy.com/the-web-developer-bootcamp/). YelpCamp is a website built using NodeJS, mongodb, and express. It's a site using which users can add and view campgrounds across the US. It support user authentication, comments, add new campsites, location using google maps, search feature...

## Project Files
If you would like to view the project files, you can find them at cloud9.
https://ide.c9.io/badawi/webdevbootcamp/

# Setup

Different setups are needed if you plan on using YelpCamp locally (or Cloud9) verus the Heroku + MongoLab setup.  This is accomplished using enviornment variables.

## Local/Cloud9 Setup

Run the following commands in the terminal.  Be sure to update information as necessary.

```
export DATABASEURL=mongodb://localhost/yelp_camp
export SESSION_SECRET=Whatever phrase you choose

```

## Heroku + MongoLab setup

Update the variables as follows:

**DATABASEURL** 'mongodb://\<dbuser>:\<dbpassword>@1234.mlab.<span></span>com:19990/yelp-camp'  
**SESSION_SECRET** 'Whatever phrase you choose'


This can be accomplished on the Heroku site by accessing the Config Vars on the Settings page.  
Alternatively this can be done on the command line with the following commands:

```
heroku config:set DATABASEURL='mongodb://\<dbuser>:\<dbpassword>@1234.mlab.<span></span>com:19990/yelp-camp'
heroku config:set SESSION_SECRET='Whatever phrase you choose'
```

# Deployed

The app is deployed at (https://azizyelpcamp.herokuapp.com/) at Heroku (also using [MongoLab](http://mlab.com)).
