# Ansible_Learning

- installation
   https://docs.ansible.com/ansible/latest/installation_guide/installation_distros.html
- Create Host file - here "shost" is host filename <br />
    vim shost   <br />
    10.30.48.130 <br />
  
  -i use to create hostfile anywhere
  ## To Run  playbook ,Use Below command:
  ansible-playbook  1.yml  -i shost --ask-pass
  
  
- 1.yml -> basic (Target section)
- 2.yml -> install httpd or any 
- 3.yml -> install HTTPD using Variable
- 4.yml -> handlers 
- 5.yml -> Loops
- 6.yml -> Conditional 

### To Run roles playbook , run Below commands
- cd play <br />
ansible-playbook master.yml -i shost --ask-pass



##### [All modules] (https://docs.ansible.com/ansible/2.9/modules/file_module.html#file-module)

