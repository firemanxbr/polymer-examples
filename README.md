# polymer-examples
My Polymer examples 



# 1
# video
# https://www.youtube.com/watch?v=y-yugxn9_ec&list=PLPaj_o9gjMYll0sSb47TrzQCjIo5iqQZm&index=1

1 - create a dir for your project
$ mkdir polymer-examples

2 - install polymer-cli
$ cd polymer-examples/
$ npm install -g polymer-cli

3 - Start bower
$ bower init
(all questions press space)

4 - check polymer versions
$ bower info Polymer/polymer

5 - install polymer
$ bower install Polymer/polymer --save
(install latest version)



# 2
# video
# https://www.youtube.com/watch?v=lhGUbyRsJc4&index=2&list=PLPaj_o9gjMYll0sSb47TrzQCjIo5iqQZm

1 - install polymer elements
$ cd polymer-examples/
$ bower install polymerelements/iron-elements --save
$ bower install polymerelements/paper-elements --save

2 - create a index.html (see example in code)
$ polymer serve
(for test you index.html or another components in this path: http://localhost:8080/bower_components/paper-input/demo/, for example)



# 3
# video
# https://www.youtube.com/watch?v=dMtnllatakc&index=3&list=PLPaj_o9gjMYll0sSb47TrzQCjIo5iqQZm

1 - install google webcomponents
$ cd polymer-examples/
$ bower install googlewebcomponents/google-web-components --save
