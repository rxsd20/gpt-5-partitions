# -*- mode: ruby -*-
# vi: set ft=ruby :
   
Vagrant.configure("2") do |config|
  config.vm.box = "generic/debian9"
  config.vm.network "private_network", ip: "192.168.121.239"
  config.vm.provider "libvirt" do |v|
    v.memory = 1024
    v.cpus = 1    
    v.storage :file, :size => '2G', :bus => 'virtio', :type => 'qcow2'
    v.storage :file, :size => '2G', :bus => 'virtio', :type => 'qcow2'
    v.storage :file, :size => '2G', :bus => 'virtio', :type => 'qcow2'
    v.storage :file, :size => '2G', :bus => 'virtio', :type => 'qcow2'
    v.storage :file, :size => '2G', :bus => 'virtio', :type => 'qcow2'
    v.storage :file, :size => '2G', :bus => 'virtio', :type => 'qcow2'
  end
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "gpt-5partitions.yml"
  end
end
