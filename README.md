#### Files in the "address" directory

- [webserver.js](webserver.js) : a NodeJS Express HTTP Server that serves the client files.
- [docroot/index.html](docroot/index.html) : Client HTML, includes Client JavaScript functions
- [docroot/firebase-messaging-sw.js](docroot/firebase-messaging-sw.js) : Background notification processing
- [app.json](app.json) : Heroku deployment file.
- [package.json](package.json) : Heroku deployment file.

# Twilio Notify Web Application Implementation

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/tigerfarm/notifywebdeploy)

For documentation and implementation details, see:
[GitHub repository](https://github.com/tigerfarm/notifyweb)

Creating the Heroku application, setting up the GitHub for Heroku link, 
and set applicatoin environment variables in Heroku.
````
$ heroku create notifywebdeploy
$ heroku git:remote -a notifywebdeploy
$ git push heroku main

$ ./setheroku.sh

For reference:
$ heroku logs --tail
$ heroku dyno:restart
$ git push -u --force origin main
````

--------------------------------------------------------------------------------

Cheers...
