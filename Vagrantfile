# vi: set ft=ruby :
# -*- mode: ruby -*-

Vagrant.configure("2") do |config|

	config.vm.provider "virtualbox" do |vb|
		vb.name = "MakerBoard OS Build VM"
		vb.memory = "4096"
	end
	
	config.vm.box = "bento/debian-10.0"
	config.vm.provision "shell", path: "vm-bootstrap.sh"
end
