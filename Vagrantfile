Vagrant.configure("2") do |config|

  config.vm.box = "terrywang/archlinux"
  config.vm.provider "virtualbox" do |vb|
    vb.name = "RPi Arch Linux Cross Compiler"
    vb.memory = 1024
    vb.cpus = 4
  end

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yml"
  end

end