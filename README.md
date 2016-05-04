# heroku-buildpack-multi

Use multiple buildpacks on your app

## Usage

    $ heroku buildpacks:set https://github.com/djmattyg007/heroku-buildpack-multi.git

    $ cat buildpacks.txt
    https://github.com/djmattyg007/heroku-buildpack-sassc.git#1.3.0
    https://github.com/heroku/heroku-buildpack-python.git#v80
    https://github.com/heroku/heroku-buildpack-php.git#v101

## License

MIT
