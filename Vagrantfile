# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu14-04"
    config.vm.box_url = "https://github.com/kraksoft/vagrant-box-ubuntu/releases/download/14.04/ubuntu-14.04-amd64.box"

  # hosts
  config.vm.define :node1 do |node1|
    node1.vm.box = "ubuntu14-04"
    node1.vm.network "private_network", ip: "192.168.33.10"
  end
  config.vm.define :node2 do |node2|
    node2.vm.box = "ubuntu14-04"
    node2.vm.network "private_network", ip: "192.168.33.11"
  end

end
