nicenemo.docker
=========

Provides Community edition of Docker and `docker-cli` for Debian systems.
With the latest version of `docker-compose`, installed via pip.

Requirements
------------

Any bare metal machine, VM, zone, or LX container with Debian that is able to run Docker.

Role Variables
--------------
None.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```YAML
---
- name: Provide Docker host.
  hosts: dockerhosts
  become: true
  roles:
    - nicenemo.docker
  #... 
```

I personally use this to host Docker images for local network management and to quickly
set up a docker host in a Proxmox Container.

License
-------

MIT

Author Information
------------------

[Hans Kruse](https://hanskruse.eu)
