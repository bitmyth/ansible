ansible-playbook docker-ubuntu.yml kubeadm-ubuntu.yml kubeadm-init-ubuntu.yml
ssh aws-singapore-1 sudo cat /etc/kubernetes/admin.conf > ~/.kube/config
