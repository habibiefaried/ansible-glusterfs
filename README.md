# ansible-glusterfs
Installation of glusterFS

# Run
ansible-playbook -i hosts all.yaml

# Output
Peered glusterFS with installed glusterFS client as well

# WARNING
Cannot be used in AWS using public IP since it's NATed. The IP must be listed in interface as well!