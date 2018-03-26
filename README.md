Ansible playbooks for intalling different sotware.

You are free to use the playbooks in your environment as long as you understand the license that has been attached to it.

I will continuously work on these playbooks and try to improve them. Please remember, I too am learning so there may be mistakes every now and then. Let me know what issues you are facing and I will get back to you as soon as possible.

To install jenkins, download the repo, go into Jenkins folder, modify the hosts file and run the below example command:

#this is a sample command, please adjust the below command with suitable parameters according to your environment.

ansible-playbook -i hosts  playbook.yml --extra-vars "target=alias_of_your_host" -vv
