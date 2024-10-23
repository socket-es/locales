# Ansible Role: locales

An Ansible Role that config Locales on Debian/Ubuntu.

## Requirements

None

## Role Variables

### Default locale for system-wide change according to your needs

```
default_locale: es_ES.UTF-8
```

### Additional locales system-wide change according to your needs

```
locales:
  - es_ES ISO-8859-1
  - es_ES.UTF-8 UTF-8
  - es_ES@euro ISO-8859-15
  - en_GB ISO-8859-1
  - en_GB.ISO-8859-15 ISO-8859-15
  - en_GB.UTF-8 UTF-8
```

## Dependencies

None

## Example

```yaml
---
- hosts: all
  roles:
    - socket_es.locales
```
## License

MIT

## Author Information

This role was created in 2024 by [Juan Carlos Giménez Moncada](https://www.opensocket.es/).
