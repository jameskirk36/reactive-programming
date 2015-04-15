# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"

  config.vm.provider "virtualbox" do |v|
    v.gui = true
  end

  # networking 
  config.vm.hostname = "reactive-devenv"

  # provisioning
  config.vm.provision :shell, path: "bootstrap.sh"
end
