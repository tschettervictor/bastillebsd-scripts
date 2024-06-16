# Guacamole
Bastille template to bootstrap Guacamole. This template will install Guacamole using the MariaDB database. It will randomly generate secure database passwords and store them in the jail root at ${JAIL_NAME}_info.txt

## Bootstrap
```shell
bastille bootstrap https://github.com/tschettervictor/bastillebsd-templates/guacamole
```

## Usage
```shell
bastille template TARGET bastillebsd-templates/guacamole
```
