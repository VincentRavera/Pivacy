PI hole
=========

Setup pi-hole via podman for a raspberry pi.

Role Variables
--------------

- pihole_image: (string) the image of pihole
- pihole_password: (string) the password of admin pihole
- extra_server: (array of dict) list of local server you want to connect to.
   - name: (string) hostname, will be added as dns record
   - ip: (string) ip of your server

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Installing PI HOLE
      hosts: servers
      roles:
         - pihole

