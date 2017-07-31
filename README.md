# informix-client-container

Add Informix Client to your [Ansible Container](https://github.com/ansible/ansible-container) project.


Mount the directory with client installer to /installers/informix (default).

```
# Set the working directory to your Ansible Container project root
$ cd myproject

# Install the service
$ ansible-container install ansible.informix-client-container
```