# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
  
  config.vm.define "shell" do |shell|
    shell.vm.box = "centos/7"
    shell.vm.hostname = "shell"
    shell.vm.network "private_network", ip: "192.168.10.30"
  end

end
