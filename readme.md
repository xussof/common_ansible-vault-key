common_ansible-vault-key

=========

This role will generate a key for ansible-vault on:
"/{{ host_root_dir }}/{{ keys_dir }}/{{ project }}/.vault-pass"

Requirements
------------

All dependencies will appear on requirements.yml file

Role Variables
--------------
#Example vars:

#create_destroy: create
#create, destroy

#renew: true
#true, false

#Name of the project this key will work for
#project: arsolute

Dependencies
------------

All dependencies will appear on requirements.yml file

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: xussof.common_ansible-vault-key }

License
-------

BSD

Author Information
------------------
Made by @xussof
