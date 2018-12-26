# UNDER CONTRUCTION 

Ansible Role to deploy the main topics of Undecloud and Overcloud lab

- Undercloud Deployment
- Overcloud image build and upload
- VBMC Configuration 

It's necessary to configure all variables in undercloud_vars.yaml before start the deployment. 

Ansible playbook execution 

```bash 
ansible-playbook -i hosts undercloud.yaml
```
