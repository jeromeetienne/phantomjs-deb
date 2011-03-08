tools to make phantom.js available on ubuntu repository

To install it:

    sudo add-apt-repository ppa:jerome-etienne/neoip && sudo apt-get update && sudo apt-get install phantomjs

phantomjs will be automatically updated when you do the usual apt-get upgrade

    $ phantomjs /usr/share/doc/phantomjs/examples/hello.js 
    Hello, world!

to install dependancies

    sudo sh deps.sh