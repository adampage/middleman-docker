## Install

Initialize Docker:

`docker-compose build`

Initalize Middleman (if starting fresh):

1. `docker-compose run web middleman init`
2. `n`, when prompted to overwrite of `Gemfile` Allowing overwrite will
   change `middleman-autoprefixer` to [problematic
   version](https://github.com/middleman/middleman/issues/2480#issuecomment-864245358).

## Run

To serve:

`docker-compose up`

To build:

`docker-compose run web middleman build`

## Reference

* https://docs.docker.com/samples/rails/
* https://gist.github.com/eemi/61617a360b55476cc5150b1853303798
* https://github.com/middleman/middleman/issues/2480#issuecomment-864245358
