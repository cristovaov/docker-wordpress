# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
   config.vm.box = "cristovaov/tenderloin"
   config.vm.network "private_network", ip: "192.168.50.4"
   config.vm.synced_folder ".", "/vagrant", type: "smb"
end
