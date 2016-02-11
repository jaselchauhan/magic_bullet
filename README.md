# magic_bullet
.zsh script to auto set up barebones express and sinatra files

N.B this is a first pass at this script - the basic functionality is there but please note it is work in progress. Any suggestions for additions are also welcome!

Instructions for Use:

N.B. .the below instructions are designed for use with Sublime Text Editor. If you have a different editor please consider when doing step 1.

1. Go to Terminal and execute following command : sublime ~/.zshrc
2. Copy the two long lines of code from the magic_bullet.txt file
3. At the bottom of .zshrc file paste the two copied lines and save.
4. In Terminal run source ~/.zshrc  to update zsh
5. Create a folder for your new app and cd into it
6. Type either "ratpack!" (for Ruby Sinatra) or "runforrest!" (for express javascript) and go get yourself a coffee - you've just saved 5 mins of tedious setup.


What Am I Actually Installing when I run the runforrest! or ratpack! command?

It's a good question, to which we have the answer! Basically you are creating the basic file structure of a Sinatra or Express App, so config, controllers, data, public, views folders as well as a main app file will be created. These are files and folders which are used in pretty much all Sinatra/Express apps so by running this you'll save yourself the hassle of manually setting these up....which means more time for thinking about stuff that matters.....or drinking some tasty coffee.

Enjoy!
