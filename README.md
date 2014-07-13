TweetFeed
=========

***DEMO*** : http://rahatol.com:8080


To start right up, open a terminal and clone the project into your desired directory and cd into it.

    git clone https://github.com/sinanm89/TweetFeed.git 

    cd ./TweetFeed/myapp

For ubuntu users only, otherwise install these manually.

    sudo apt-get install npm, nodejs, mongodb

Install everything and create directories for mongodb.

    npm install

    cd ./config

    mkdir mongodb/log/; mkdir mongodb/srv; mkdir mongodb/srv/db; touch mongodb/log/mongod.log;

Start mongodb

    mongod -f ./config/mongodb/mongodb.conf

Start the webapp

    node app.js &
