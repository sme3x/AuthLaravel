## Install

`./vendor/bin/sail up`

`./vendor/bin/sail down`

You can tesst login trough Postman. Example:

```
http://localhost/api/login

body:
email: test@gmail.com
password: test
```

and then call:

```
http://localhost/api/users
```

## Known issues

If you have problems with `./vendor/bin/sail up` then run code below:

```
docker-compose down --volumes
./vendor/bin/sail up
```
