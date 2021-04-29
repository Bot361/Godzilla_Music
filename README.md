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
