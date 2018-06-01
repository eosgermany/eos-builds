EOS Canada builds of EOSIO Software
-----------------------------------

This repository contains Dockerfiles used to build EOSIO Software.

It also builds contracts from https://github.com/eoscanada/eos-bios
(`eosio.disco` and `eosio.unregd`)

Images are pushed to https://hub.docker.com/r/eoscanada/eos

In case the latest docker images are not available, please use the following commands:

$ docker build -t eosio-build-env:v7 - < Dockerfile-build-en

$ docker build -t eosgermany/eos:DAWN-2018-05-30 - < Dockerfile-nodeos
