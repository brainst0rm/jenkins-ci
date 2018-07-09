Vagrant.configure("2") do |config|


  config.vm.define "jenkins" do |jenkins|
     jenkins.vm.box = "bento/ubuntu-16.04"
     jenkins.vm.hostname = "client"
     jenkins.vm.network "private_network", ip: "192.168.33.10"
  end

  config.vm.define "server" do |server|
    server.vm.box = "bento/ubuntu-16.04"
    server.vm.hostname = "agent"
    server.vm.network "private_network", ip: "192.168.33.20"
  end
end
