Vagrant.configure("2") do |config|

  config.vm.box = "terrywang/archlinux"

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yml"
  end

end