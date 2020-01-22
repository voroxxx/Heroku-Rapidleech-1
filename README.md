# Heroku-Rapidleech
## Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

or :


Use the Deploy to Heroku button, or use the old fashioned way described below.

[Use Crypt  type for htpasswd Generator is here.](https://macminiosx.github.io/passwd-generator/)

<a href="https://heroku.com/deploy?template=https://github.com/elasa-Sites/Heroku-Rapidleech-1/tree/master">
  <img src="https://www.herokucdn.com/deploy/button.png" alt="Deploy">
</a>


## or :


`git clone https://github.com/HasibulKabir/Heroku-Rapidleech`

`cd Heroku-Rapidleech`

`heroku login`

`heroku git:remote -a xxxxx`

`heroku stack:set container`

`git push heroku HEAD:master --force`

#### Optional:

`heroku ps:scale worker=0`

`heroku ps:scale worker=1`
