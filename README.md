# Node-Npm-Installation
Node JS / NPM have become essential parts of many applications.

Because of this, and my recent experience with Node, I have decided to compile some instructions on how to install NodeJS/NPM installation [ so that you do not require the sudo command]. 

1. yum install nodejs

2. yum install npm

Tweaks
---------
$ echo prefix = ~/.node >> ~/.npmrc

$ echo 'export PATH=$HOME/.node/bin:$PATH' >> ~/.bashrc 

$ . ~/.bashrc


    Go To the project and  install all dependencies in package.json

      $ npm install

Bower
-------

npm install -g bower

    Go to project and install bower dependencies mentioned in bower.json

      $ bower update

===============================================================================================

Grunt Task Runner
-----------------
npm install -g grunt-cli

[ Install ruby and gem install sass]


************************ U are all set to FLY #Puff #Puff ****************************
