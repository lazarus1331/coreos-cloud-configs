# coreos-cloud-configs
Cloud configs to configure CoreOS for different purposes

## Description
CoreOS (and many cloud providers) allows for the use of a cloud-config file, which can perform basic provisioning of the hosts without the need for an external configuration server.  It also allows configuration of systemd services, which is the purpose here.

## Testing
The [coreos-vagrant](https://github.com/coreos/coreos-vagrant.git) was used in the development and testing of these cloud-configs.

# Usage
If using coreos-vagrant:
Copy the cloud-config you want to use into the coreos-vagrant directory, and name it 'user-data'. Then run ```vagrant up```

# Credits
Based upon the excellent work of [Jeff Lindsay](http://progrium.com/blog/2014/08/20/consul-service-discovery-with-docker/)
