# openldap docker container

- Start the container

`docker-compose up`

- Administrate the LDAP server
```
URL
https://localhost:6443/

Login DN
cn=admin,dc=example,dc=org

Password
changethis
``` 

- Update the `config.yml` file of the Wazuh indexer with details of the LDAP server
