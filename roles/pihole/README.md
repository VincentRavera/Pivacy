PI hole
=========

Setup pi-hole via podman for a raspberry pi.

Role Variables
--------------

- pihole_image: (string) the image of pihole
- pihole_password: (string) the password of admin pihole

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Installing PI HOLE
      hosts: servers
      roles:
         - pihole

