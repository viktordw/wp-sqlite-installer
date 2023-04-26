# Portable wordpress playground
With sqlite instead of mysql server and using php local server, without needing apache or other separate web server.


## Install Naked Wordpress with SQLite database configured

```
./install.sh
```


## Run

```
./run.sh
```

Runs a local php server and prints out the address with port. Default is 8011


## Set up wordpress installation, plugins, theme, settings, options CLI

With installing and using wpcli:

```
./configure-wp.sh
```

Installs wordpress with default port and creates and admin user (with password: admin) 


## Clean up

```
./cleanup.sh
```

Basically reerts everything (deletes wp, db, and leave the core scripts).


## References

SQLite integration (db.sql) is from https://github.com/aaemnnosttv/wp-sqlite-db <br>
Portable Wordpress with SQLite instead of MySQL https://dev.to/mfyz/portable-wordpress-with-sqlite-instead-of-mysql-4lj1
