# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
 
  config.vm.box = "centos/8"

  config.vm.provider "virtualbox" do |vb|
    vb.gui = true
    vb.memory = "2048"
   end

  config.vm.provision "ansible_local" do |ansible|
    ansible.playbook = "ansible/main.yaml"
    ansible.install_mode = "default"
    ansible.version = "2.9.9"
    ansible.compatibility_mode = "2.0"
  end
end
