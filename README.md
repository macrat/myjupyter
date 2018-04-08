My JupyterLab container

## how to deploy
1. Make password
``` shell
$ ./makepassword.sh
```

Or, write [hashed password](http://ipython.readthedocs.io/en/stable/api/generated/IPython.lib.security.html#IPython.lib.security.passwd) into `.env`. Please see [.env.example](./.env.example).

2. Run
``` shell
$ docker-compose up -d
```

3. Use
Access to http://localhost:8888
