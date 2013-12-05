mruby-buildpack
===============

## License
* MIT License
* Copyright (C) 2013 Takeshi Watanabe

## Description
* buildpack for mruby app.

## Howto use this
* place *build_config.rb* and *server.rb* in root directory of the repo.
  * *build_config.rb* will be used to build slug.
  * *server.rb* will be runned in app when no Procfile is specified.

## libuv
* lastest stable libuv release will be build before mruby to use it with [mruby-uv](https://github.com/mattn/mruby-uv)
