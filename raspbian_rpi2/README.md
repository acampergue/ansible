# What does this playbook

install dhcpcd et configure
upgrade all packages
prepare tmpfs mounts and mount them

TODO: authorized_keys

# How to use
~~~~
ansible-playbook -i hosts site.yml --extra-vars="torguard_user=<USER_NAME> torguard_password=<PASSWORD>" -v
~~~~
