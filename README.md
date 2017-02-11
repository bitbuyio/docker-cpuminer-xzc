# docker-cpuminer-xzc
Docker Container that runs https://github.com/zcoinofficial/cpuminer-xzc

##Run

Replace the [Pool URL], [Username] and [Password] with your own values and run

```docker run --name miner -d -e URL=[Pool URL] -e USERNAME=[Username] -e PASSWORD=[Password] wesseloc/docker-cpuminer-xzc ```

##Terminology

###Pool Address

The address of the mining pool see below for details:
* MiningPoolHub [https://zcoin.miningpoolhub.com/]
* Pool.mn [https://pool.mn/xzc/]
* Suprnova [https://xzc.suprnova.cc/]
* MaxMiners [https://xzc.maxminers.net/]

###Username
Worker username at the pool

###Password
Worker password at the pool

## Zcoin Pool guide

See the pool mining guide at https://github.com/zcoinofficial/zcoin/wiki/Pool-Mining-Guide

## Donations
Did this container make your life easier, buy me a coffee:

  BTC: 3H6bvf9ZZ4PJoebGxBef9Kw92P88KsEaxF

  XZC: a46WE4GECjXWEGjbHWRGBLSCzhiuYsUFgH

