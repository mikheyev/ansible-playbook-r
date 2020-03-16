# ansible-playbook-r
An Ansible Playbook to deploy RStudio Server

```sh

sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt-get install git ansible
git clone https://github.com/yutannihilation/ansible-playbook-r
ansible-playbook ansible-playbook-r/deploy-rstudio-server.yml
```

[Instructions](https://github.com/grantmcdermott/rstudio-compute-engine) to have this run on Google Compute Engine

```
sudo gcloud compute firewall-rules create allow-rstudio --allow=tcp:8787
```
