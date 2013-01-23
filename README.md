Vagrant File & Chef file for Ubuntu Box

- Install a Standard Web stack (Apache, PHP, MySQL)
- Install Postgres, Mongodb
- Imagemagick
- NodeJS & npm
- RVM, Ruby 1.9.3 & Rails stack
- Composer installation
- Symfony install thru Composer

Prerequisite gem : Vagrant, Librarian

Usage : 
Clone the Git Repository :
- git clone  https://github.com/gpsnail/VagrantBox.git

Execute bundle install command to install all required Gem

Inside the chef-repo folder, execute foolowing recipe to get the latest chef Cookbook.
- librarian-chef install

Then you have to install a box as empty as possible : 
- vagrant box 'myminibox' urltotheboxfile

Launching the box :
- vagrant up 

Will install the box and provision using the chef repo

I can provide an empty ubuntu box on demand
