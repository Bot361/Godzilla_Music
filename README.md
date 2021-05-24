## Deploying

#### Note - Change appname to any other name

    heroku login

    heroku create appname
 
    heroku buildpacks:add https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git -a appname

    heroku buildpacks:add https://github.com/heroku/heroku-buildpack-python.git -a appname

    git init

    heroku git:remote -a appname

    git add .

    git commit -am "Your commit message"

    git push heroku master

    heroku ps:scale worker=1




## Deploy To Heroku</h4>

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Bot361/Godzilla_Music)

Get pyrogram STRING_NAME from here:

[![GenerateString](https://img.shields.io/badge/repl.it-generateString-yellowgreen)](https://replit.com/@subinps/getStringName)
