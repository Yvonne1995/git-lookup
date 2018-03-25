# Git Hub Search

## CONTRIBUTORS
Kodhe Joshua

## DESCRIPTION OF PROJECT PURPOSE
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.3.

It is an application where users can search on Github for users using their user names. 

## COMPLETE SETUP/INSTALLATION REQUIREMENTS
In order to be able to use this application or edit it you will need to Install:
  1. Node
    Visit the [node download page](https://nodejs.org/en/download/package-manager/ (Links to an external site.))
  2. Angular  
      Angular CLI installation.(Linux)
      -On the terminal
        :~$ npm install -g @angular/cli
      Confirmation
          :~$ ng
  3. Watchman
      -Linux installation.
      $ cd ~
      $ git clone https://github.com/facebook/watchman.git
      $ cd watchman/
      $ git checkout v4.7.0
      $ sudo apt-get install -y autoconf automake build-essential python-dev
      $ ./autogen.sh
      $ ./configure
      $ make
      $ sudo make install

      $ watchman --version
      $ echo 999999 | sudo tee -a /proc/sys/fs/inotify/max_user_watches  && echo 999999 | sudo tee -a  /proc/sys/fs/inotify/max_queued_events && echo 999999 | sudo tee  -a /proc/sys/fs/inotify/max_user_instances && watchman  shutdown-server

## LICENSE INFORMATION AND COPY RIGHT
[MIT](license)
