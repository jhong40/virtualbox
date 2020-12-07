# virtualbox

Install ubunto Linux quickly without going throug the installation process

### Choice 1: download ubuntu image from https://www.osboxes.org/virtualbox-images/
   Virtualbox->Machine->New->...->Use existing Virtual disk image (browse to the image downloaded above)
   password: "osboxes.org"

### Choice2: (tutorial: https://learn.hashicorp.com/tutorials/vagrant/getting-started-index?in=vagrant/getting-started)
  * install vagrant (https://www.vagrantup.com/downloads)
  * create new folder 
  * copy the Vagrantfile (from this repository) into the new folder
  * cd 'newfolder'
  * run `vagrant up`  # will download ubuntu image (if image not exist locally), create (if not created) and run the vm, may take sometime to download 1st time
  * run `vagrant halt` # stop the vm  
  * run `vagrant status` # check status
  * run `vagrant ssh default` # ssh connect to the vm

  
  
  
