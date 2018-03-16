# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "bento/fedora-27"
  config.vm.provision "shell", inline: "sudo -u vagrant sh -c 'echo set editing-mode vi > ~vagrant/.inputrc'"
  config.vm.provision "shell", inline: "sudo dnf install screen -y"
end
