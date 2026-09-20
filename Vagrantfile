Vagrant.configure("2") do |config|

  config.vm.box = "pano/debian-13.6-server"
  config.vm.box_url = File.expand_path("metadata.json", __dir__)

  config.vm.provider "virtualbox" do |vb|
    vb.memory = 2048
    vb.cpus = 2
  end

end
