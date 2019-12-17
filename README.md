# HerokuGlypeProxy


==> Last Update - Dec,2019


==> Active Contributors - 1

==> Notes
* RAR5 Is Now Supported.

==> Script Information
My own config of Glype PHP proxy for Heroku

## Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

##  Or do this in remote server like https://codeanywhere.com/editor/

```
#!/bin/bash 
sudo curl https://cli-assets.heroku.com/install-ubuntu.sh | sh
heroku login 
#another mthod

#git clone https://github.com/Heroku-elasa/HerokuGlypeProxy
git clone https://github.com/Heroku-elasa/HerokuGlypeProxy
cd h*
sudo git init
sudo git add .
 sudo git add -f */*/*
sudo git commit -m "initial commit"

sudo heroku create --buildpack https://github.com/heroku/heroku-buildpack-php --region eu

sudo git push heroku master

