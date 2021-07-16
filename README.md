Don't forget to add a line in your /etc/hosts file per each site you want to add:

```
127.0.0.1	hosta
127.0.0.1	hostb
```

Before running docker-componse up -d create a .env file to setup the appropiated values as follows:

```
MY_HOST=
HOST_EMAIL=
Authentication_Microsoft_ClientId=
Authentication_Microsoft_ClientSecret=
Jwt_Key=
```