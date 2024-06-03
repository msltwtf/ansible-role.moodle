# Ansible Role: Moodle
[![CI](https://github.com/msltwtf/ansible-role.moodle/actions/workflows/ci.yml/badge.svg)](https://github.com/msltwtf/ansible-role.moodle/actions/workflows/ci.yml)  
Install php and php-modules in a specific version from the sury.org repo.

[Changelog](CHANGELOG.md)

# Requirements

* Running Database
* Configured Webserver

# Role Variables

Available variables are listed below, along with default values from `defaults/main.yml`

## moodle_version

```yaml
moodle_version: 404
```

The Moodle version to be installed.

---

## moodle_webroot

```yaml
moodle_webroot: /var/www/moodle
```

Filesystem path for the webroot data.

---

## moodle_data_path

```yaml
moodle_data_path: /var/www/moodledata
```

FS path for the moodle data.

---

## moodle_domain

```yaml
moodle_domain: ''
```

FQDN for the moodle frontend.

---

## moodle_mysql_host

```yaml
moodle_mysql_host: localhost
```

Hostname of the MySQL/MariaDB database.

---

## moodle_mysql_login_user

```yaml
moodle_mysql_login_user: root
```

Username to use for all DB config related tasks.

---

## moodle_mysql_login_password

```yaml
moodle_mysql_login_password: ''
```

Password to use for all DB config related tasks.

---

## moodle_mysql_username

```yaml
moodle_mysql_username: moodle
```

Database username for the moodle system to use.

---

## moodle_mysql_password

```yaml
moodle_mysql_password: ''
```

Database password for the moodle system to use.

---

## moodle_mysql_database

```yaml
moodle_mysql_database: moodle
```

Database name to use.

---

# Dependencies

None.

# License

MIT
