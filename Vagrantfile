# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure("2") do |config|
  
  config.vm.box_url = "/home/vagrant/vagrant_projects/vagrant-lxc/boxes/output/vagrant-lxc-precise-amd64-2013-10-26.box"
  config.vm.box = "precise"
  
  config.vm.provider :lxc do |lxc|
    lxc.customize 'utsname', 'test'
    lxc.customize 'cgroup.memory.limit_in_bytes', '1024M'
    lxc.customize 'network.ipv4', '10.22.22.100'
  end
end

   
				   
