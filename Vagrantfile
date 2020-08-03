Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"
  config.vm.hostname = "zakdocker"
  config.vm.provision "shell", path:"docker.sh"
end