Docker silex
============

Silex The PHP micro-framework based on the Symfony2 Components

Quick Start
-----------

`docker run -d --name silex -p 80:80 -it jcherqui/silex:latest`

You can add a shared directory as a volume directory with the argument -v /your-path/files/:/var/www/ like this :

`docker run -d --name silex -p 80:80 -v $PWD:/var/www/ -it jcherqui/silex:latest`


License
----

MIT


**Free Software, Hell Yeah!**
