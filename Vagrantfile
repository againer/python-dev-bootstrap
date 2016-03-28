Vagrant.configure("2") do |config|

  config.vm.box     = 'PythonDevBootstrap_13_10'
  config.vm.box_url = "http://puppet-vagrant-boxes.puppetlabs.com/ubuntu-1310-x64-virtualbox-nocm.box"

  #network
  config.vm.network :private_network, ip: "192.168.33.10"
  
  #shared
  config.vm.synced_folder "./projects", "/projects", type: 'nfs'

end
