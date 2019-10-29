Clone this repo and then run the playbook as follows:

cd share_vars_across_roles

ansible-playbook site.yml -e "location=new_york" 

or 

ansible-playbook site.yml -e "location=london"
