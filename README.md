# virtualbox


Install ubunto Linux quickly without going throug the installation process

[justmeandopensource](https://github.com/justmeandopensource/vagrant/blob/master/vagrantfiles/ubuntu18/Vagrantfile)


### Installation: dependency VC++ 2019 and python win32
- https://aka.ms/vs/17/release/vc_redist.x64.exe	
- install python
- pip install pywin32


### Choice 1: OSBoxes [download ubuntu image](https://www.osboxes.org/virtualbox-images/)
   * Virtualbox->Machine->New->...->Use existing Virtual disk image (https://www.osboxes.org/guide/)
   * password: "osboxes.org"

### Choice2: Vagrant ([tutorial](https://learn.hashicorp.com/tutorials/vagrant/getting-started-index?in=vagrant/getting-started))
  * install vagrant: [Download](https://www.vagrantup.com/downloads)
  * create new folder 
  * copy the Vagrantfile (from this repository) into the new folder
  * cd 'newfolder'
  * run `vagrant up`  # will download ubuntu image (if image not exist locally), create (if not created) and run the vm, may take sometime to download 1st time
  * run `vagrant halt` # stop the vm  
  * run `vagrant status` # check status
  * run `vagrant ssh default` # ssh connect to the vm
  * run `vagrant ssh host1`
  * run `vagrant destroy`  # destroy vm with prompt
  * run `vagrant destroy -f` # destroy without prompt

  
  
  
