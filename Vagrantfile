Vagrant.configure("2") do |config|

    config.vm.provision "shell", inline: "echo Hello"

      config.vm.define "virtualMachine1" do |virtualMachine1|
            virtualMachine1.vm.box = "hashicorp/bionic64"
              end
end
