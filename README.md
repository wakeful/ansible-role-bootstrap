# bootstrap machines with Ansible

- [Ansible](https://www.ansible.com) Simple IT Automation.

## Variables

- bootstrap_user: adrian
    - bootstrap a new user with specific name

- bootstrap_group: ops
    - name of the primary group for the bootstrap user

- bootstrap_authorized_key: [https://raw.githubusercontent.com/wakeful/.pub/master/id_rsa_48k.pub](https://raw.githubusercontent.com/wakeful/.pub/master/id_rsa_48k.pub)
    - authorized key for the bootstrap user
