# docker-build-essentials

[![](https://badge.imagelayers.io/sys42/docker-build-essentials:latest.svg)](https://imagelayers.io/?images=sys42/docker-build-essentials:latest 'Get your own badge on imagelayers.io')

Base image for Software Platforms which requires Native Compilation (NodeJS, Ruby, PHP etc.pp.)

Extends [the base image](https://github.com/sys42/docker-base) with the following packages:

  * build-essential (~110 mb)
  * git (~22 mb) 
  * python (~16 mb)

`/usr/share/doc` and `/usr/share/man` takes up 32 mb. This may be saved. But is it worth, yet? It's just less than 10 percent of the total size (389 mb).
   
For generic usage informations please examine [the README file of the base image](https://github.com/sys42/docker-base).
