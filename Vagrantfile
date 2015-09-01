# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  config.vm.box = "ubuntu/trusty64"

  # config.vm.box_check_update = false

  # config.vm.network "forwarded_port", guest: 80, host: 8080

  # config.vm.network "private_network", ip: "192.168.33.10"

  config.vm.network "public_network"

  # config.vm.synced_folder "../data", "/vagrant_data"

  # Webs
  # config.vm.define "web" do |web|
  #   web.vm.network :private_network, ip: "192.168.111.101"

  #   web.vm.provider "virtualbox" do |v|
  #     v.memory = 1024
  #   end

  #   # config.vm.provision "ansible" do |ansible|
  #   #    ansible.playbook = "playbook.yml"
  #   #    ansible.extra_vars = { ansible_ssh_user: 'vagrant' }
  #   #    ansible.raw_arguments  = [
  #   #       "--private-key=/.vagrant/machines/web/virtualbox/private_key"
  #   #     ]
  #   # end
  # end

  # config.vm.define "load_balancer" do |lb|
  #   lb.vm.network :private_network, ip: "192.168.111.105"
  #   lb.vm.provider "virtualbox" do |v|
  #     v.memory = 256
  #   end
  # end

  config.vm.define "survey" do |lb|
    lb.vm.network :private_network, ip: "192.168.111.104"
    lb.vm.provider "virtualbox" do |v|
      v.memory = 1024
    end
  end

  # config.vm.define "db" do |db|
  #   db.vm.network "public_network"
  #   db.vm.network :private_network, ip: "192.168.111.102"
  #   db.vm.provider "virtualbox" do |v|
  #     v.memory = 256
  #   end
  # end


end
