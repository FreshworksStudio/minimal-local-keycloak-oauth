# Minimal Keycloak + OAuth proxy set-up
Docker compose for locally spinning up Keycloak and protecting a web service.

# Quickstart

```
make start
```

Visit http://willisthegreatest.local.freshworks.club:8081

# Tailing logs

```
make logs
```

# To Do
- Secrets and properties templated in from `.env`
- Specific versions of docker images
- GitHub action to run automated tests against this local deployment
