Node js can be used to run Javascript outside of a web browser.
Express.js works with node js as a mean to run a simple web server
A webserver is hardware or software or both that can be store, process, and deliver website content

### Getting set up with Node
In the console, in the directory you want your program to be in, run `npm init -y`
Without the `-y` you will be asked a bunch of questions about your projects. The `y` just leaves the
defaults.
npm - node package manager (like pip in python) used to install other js libraries into your
*always* .gitignore the folder `node_modules`
Starting and stopping a server to test can be a pain. Use nodemon - `npm install --save-dev nodemon`
the `--save-dev` means it only needs installed when in development environments. See package.json