$script = <<SCRIPT
apt-get update
apt-get -y install git-core
SCRIPT

Vagrant.configure("2") do |config|

  config.vm.box = 'ubuntu'
  
  config.vm.box_url = 'http://files.vagrantup.com/precise64.box'

  config.vm.provision "shell", inline: $script

end
