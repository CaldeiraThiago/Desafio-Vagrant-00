
Vagrant.configure("2") do |config|

    config.vm.box = "ubuntu/focal64"

    config.vm.network "public_network", bridge: "wlo1"

    config.vm.provider "virtualbox" do |vb|

        vb.memory = "1024"
        vb.name = "ubuntu-20.04"
        vb.cpus = "1"
    end
end
