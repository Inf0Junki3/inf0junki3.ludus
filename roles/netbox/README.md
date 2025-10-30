Netbox
=========

Sets up the Netbox network & infrastructure management solution.

Role variables
--------------

- GENERIC_TIMEZONE: "America/New_York"
- TZ: "America/New_York"
- PUID: "1000"
- PGID: "1000"
- POSTGRES_USER: postgres
- POSTGRES_DB: netbox
- SUPERUSER_EMAIL: "itsame@mario.time"
- SUPERUSER_PASSWORD: "password"
- ALLOWED_HOST: "netbox.ludus.domain"
- DB_NAME: "netbox"
- DB_USER: "postgres"
- DB_PASSWORD: "badpassword"
- DB_HOST: "localhost"
- DB_PORT: "3306"
- REDIS_HOST: "redis"
- REDIS_PORT: ""
- REDIS_PASSWORD: "badpassword"
- REDIS_DB_TASK: ""
- REDIS_DB_CACHE: ""


Dependencies
------------

- geerlingguy.docker

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: inf0junki3.ludus.netbox }

License
-------

MIT

