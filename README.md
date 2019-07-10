#name
my-js-dev-env

#author
By Justin Adoga

# my-js-dev-env
This is my JavaScript Development environment

# This script runs before service is started --pre and post runs automatically
run: npm prestart: runs the pre-start script automatically after npm start is called

#To run your development mode without sharing on local tunnel
run: npm open:src

#To share your development app on localtunnel after app started
run: npm localtunnel

#To start and share your app on local tunnel
run: npm start
