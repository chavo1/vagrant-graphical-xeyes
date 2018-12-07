Vagrant.configure("2") do |config|
  config.vm.box = "chavo1/xenial64base"
  config.ssh.forward_x11 = true
  config.vm.provision "shell", path: "scripts/provision.sh"
end
