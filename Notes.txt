<<<<<<< HEAD
# k82-Centos7
Ansible playbooks to install Kubernetes on a Centos7 Cluster
=======
# Ansible playbooks for k8s cluster installation: created to setup a kubernetes cluster with one master node and multiple worker nodes.
# Instructions

# Prerequisites

# Modify "hosts" file with you server names in k8s-centos7 directory
# Modify Master and Worker node details in "env_variables" in k8s-centos7 directory primarily ad_addr
# Deploy the ssh key from master node to other nodes for authentication using ssh-keygen
#       Create RSA key pair
#            $ssh-keygen -t rsa # take defaults, no passphrase
#       Copy public key to 
#           $ssh-copy-id demo@198.51.100.0 # take defaults, enter password
# Verify you are able to login into any nodes without password

# Execute Ansible playbooks

# Run "settingup_kubernetes_cluster.yml" playbook to setup the cluster: ansible-playbook settingup_kubernetes_cluster.yml
# Run "join_kubernetes_workers_nodes.yml" playbook to join the worker nodes with kubernetes master node: join_kubernetes_workers_nodes.yml

# Verify the configuration
# All Nodes: kubectl version
# Master Node: kubectl get nodes
>>>>>>> Iniital Committ
