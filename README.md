ansible-playbook docker-ubuntu.yml kubeadm-ubuntu.yml kubeadm-init-ubuntu.yml
ssh aws-singapore-1 sudo cat /etc/kubernetes/admin.conf > ~/.kube/config

# Set inventory
ansible-playbook -i hosts docker-ubuntu.yml

# Build inventory
[inventory guide](https://docs.ansible.com/ansible/latest/inventory_guide/intro_inventory.html#inventory-basics-formats-hosts-and-groups)



## install ansible
[https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-and-upgrading-ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-and-upgrading-ansible)

```sh
python3 -m pip install --user ansible
```
