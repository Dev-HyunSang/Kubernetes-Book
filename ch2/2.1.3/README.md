```sh
$ vagrant init
$ vagrant up
$ vagrant ssh
```

```sh
$ vagrant up
Bringing machine 'default' up with 'virtualbox' provider...
==> default: Importing base box 'sysnet4admin/CentOS-k8s'...
==> default: Matching MAC address for NAT networking...
==> default: Checking if box 'sysnet4admin/CentOS-k8s' version '0.7.4' is up to date...
==> default: Setting the name of the VM: 213_default_1623478106016_85667
==> default: Clearing any previously set network interfaces...
==> default: Preparing network interfaces based on configuration...
    default: Adapter 1: nat
==> default: Forwarding ports...
    default: 22 (guest) => 2222 (host) (adapter 1)
==> default: Booting VM...
==> default: Waiting for machine to boot. This may take a few minutes...
    default: SSH address: 127.0.0.1:2222
    default: SSH username: vagrant
    default: SSH auth method: private key
    default: 
    default: Vagrant insecure key detected. Vagrant will automatically replace
    default: this with a newly generated keypair for 
better security.
    default: 
    default: Inserting generated public key within guest...
    default: Removing insecure key from the guest if 
it's present...
    default: Key inserted! Disconnecting and reconnecting using new SSH key...
==> default: Machine booted and ready!
==> default: Checking for guest additions in VM...
    default: The guest additions on this VM do not match the installed version of
    default: VirtualBox! In most cases this is fine, 
but in rare cases it can
    default: prevent things such as shared folders from working properly. If you see
    default: shared folder errors, please make sure the guest additions within the
    default: virtual machine match the version of VirtualBox you have installed on
    default: your host and reload your VM.
    default:
    default: Guest Additions Version: 5.2.12
    default: VirtualBox Version: 6.1
==> default: Mounting shared folders...
    default: /vagrant => D:/GitHub/Kubernetes-Book/ch2/2.1.3
Vagrant was unable to mount VirtualBox shared folders. This is usually
because the filesystem "vboxsf" is not available. This filesystem is
made available via the VirtualBox Guest Additions and kernel module.
Please verify that these guest additions are properly installed in the
guest. This is not a bug in Vagrant and is usually caused by a faulty
Vagrant box. For context, the command attempted was: 

mount -t vboxsf -o uid=1000,gid=1000,_netdev vagrant 
/vagrant

The error output from the command was:

mount: unknown filesystem type 'vboxsf'
```