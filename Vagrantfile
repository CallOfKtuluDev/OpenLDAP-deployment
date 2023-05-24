Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.box_check_update = false
  config.vm.hostname="trusty"

  config.vm.provision "ansible" do |ansible|
  ansible.playbook = "playbook.yml"
  end
 
end
