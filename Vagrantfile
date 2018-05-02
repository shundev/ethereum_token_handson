# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-17.10"
  config.vm.network "forwarded_port", guest: 9545, host: 9545 # truffle develop
  config.vm.network "forwarded_port", guest: 3000, host: 3000 # npm run dev
  config.vm.network "forwarded_port", guest: 3001, host: 3001 # npm run dev

  config.vm.provider "virtualbox" do |vb|
    vb.gui = false
    vb.customize ["modifyvm", :id, "--memory", "2048", "--cpus", "2", "--ioapic", "on"]
  end
end

