## Heroku Buildpack for Veritrans configuration file on Rails

### Usage
- add this buildpack. `heroku buildpacks:add https://github.com/Liquid-dev/heroku-buildpack-veritrans-rails.git -a app-name`
- put `tg_mdk.heroku.ini` for production.
- when deploying, copy `tg_mdk.heroku.ini` to `tg_mdk.ini`
