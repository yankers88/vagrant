

Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/trusty64"

  config.vm.box_url = "http://files.vagrantup.com/precise32.box" 

  config.vm.provision :shell, :path =>"bootstrap.sh"
  
  config.vm.network :forwarded_port, guest: 80, host:8080
end
