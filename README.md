# docker-cpuminer-xzc
Docker Container that runs https://github.com/Optiminer/cpuminer-xzc

##Run

Replace the [Pool Address], [Pool Port], [Username] and [Password] with your own values and run

```docker run --name miner -d wesseloc/docker-cpuminer-xzc ./cpuminer -a lyra2rev2  -o stratum+tcp://[Pool Address]:[Pool Port]  -u [username] -p [password]```

##Terminology

###Pool Address

The address of the mining pool see below for details:
* MiningPoolHub [https://zcoin.miningpoolhub.com/]
* Pool.mn [https://pool.mn/xzc/]
* Suprnova [https://xzc.suprnova.cc/]
* MaxMiners [https://xzc.maxminers.net/]

###Pool Port
The startum Port of the pool being used.

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

