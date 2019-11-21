Add these enviroment variables in beanstalk configuration

- GF_SERVER_ROOT_URL=grafana.example.com
- GF_SECURITY_ADMIN_PASSWORD=my_strong_password
- GF_INSTALL_PLUGINS=grafana-clock-panel,grafana-simple-json-datasource
- GF_DATABASE_URL=mysql://user:secret@host:port/database (if you are using mysql as database) 
- GF_DATABASE_URL=postgres://user:secret@host:port/database(if you are using postgres as database)