# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"

  config.vm.provision "shell", inline: <<-SHELL
    apt-get update
    apt-get install -y build-essential cmake gdb
  SHELL
  
  #config.vm.provision "shell", path: "scripts/setup_tfhe.sh"
  
end
