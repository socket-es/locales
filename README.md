# Ansible Role: locales

An Ansible Role that config Locales on Debian/Ubuntu.

## Role Variables

### Default locale for system-wide

default_locale: es_ES.UTF-8

### Additional locales system-wide

locales:
  - es_ES ISO-8859-1
  - es_ES.UTF-8 UTF-8
  - es_ES@euro ISO-8859-15
  - en_GB ISO-8859-1
  - en_GB.ISO-8859-15 ISO-8859-15
  - en_GB.UTF-8 UTF-8
