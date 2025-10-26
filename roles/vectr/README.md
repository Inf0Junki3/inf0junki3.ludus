VECTR
=========

Sets up the VECTR red/purple team platform

Dependencies
------------

geerlingguy.docker

Using your VECTR instance
-------------------------

Within your ludus range, you will no doubt want to access VECTR... To do this, there are several things that you
**must** take into consideration:

* You *must* use the hostname that you specified as `vectr_hostname` - by default `{{ range_id }}-vectr.ludus.domain`.
  If you're accessing it from your kali instance, you can either doctor your `/etc/hosts` file to point to your VECTR
  machine, or you should add an entry in your range AdGuard - see https://docs.ludus.cloud/docs/DNS/
* Remember that VECTR comes out of the box with a hard-coded user name and password, which you can get from the
  documentation here: https://docs.vectr.io/Installation/#usage

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: inf0junki3.ludus.vectr }

License
-------

MIT
