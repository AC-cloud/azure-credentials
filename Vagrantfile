# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.provider :azure do |azure|

    # Default values
    # The cerficate should be named after your subscription id using the azure-cli
    azure.mgmt_certificate = azure.subscription_id + '.pem'
    azure.mgmt_endpoint = 'https://management.core.windows.net'

    azure.subscription_id = raise "Insert subscription_id in Vagrantfile"
    azure.vm_location = 'West Europe'

  end
end
