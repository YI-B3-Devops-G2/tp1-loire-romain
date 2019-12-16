Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp/bionic64"
  config.vm.box_url = "https://vagrantcloud.com/hashicorp/bionic64"
  config.vm.provision :shell, path: "bootstrap.sh.txt"
  config.vm.network :forwarded_port, guest: 80, host: 9999
end
