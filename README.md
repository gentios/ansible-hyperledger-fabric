Role Name
=========

An ansible role to deploy hyperledger fabric in an existing kubernetes cluster

Requirements
------------

A 4+ nodes kubernetes cluster

Role Variables
--------------

Role variables are defined in defaults/main.yaml

Dependencies
------------

- [andrewrothstein.kubernetes-helm](https://galaxy.ansible.com/andrewrothstein/kubernetes-helm)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: "Deploy hyperledger network"
      hosts: dev-nodes
      remote_user: root
      become_method: su
      roles:
       - role: helm
       - role: ansible-hyperledger-fabric

License
-------

BSD

Author Information
------------------

[Gentian Elmazi](https://github.com/gentios)
