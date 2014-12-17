VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
	config.vm.box = "mitchellh/boot2docker"
	config.vm.synced_folder ".", "/vagrant", type: "rsync",
		rsync__exclude: [".git/", ".vagrant/", "Vagrantfile"]
end
