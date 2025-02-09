Squid
=========

Setup SQUID via podman for a raspberry pi.

Role Variables
--------------

- squid_image: (string) the image of squid
- local_network: (array of string) list of your network cidr
- extra_server: (array of dict) list of local server you want to connect to.
   - name: (string) Comment on your server
   - ip: (string) ip of your server
   - ports: (array of int) list of ports allowed

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Installing SQUID
      hosts: servers
      roles:
         - squid

