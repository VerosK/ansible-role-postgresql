#  Ansible Role for PostgreSQL


Ansible Role for PostgreSQL Installation.   ( work-in-progress )

##  Requirements

This role require Ansible 2.0 or higher.

This role was designed for 16.04 LTS. 

## Role Variables

Check `defaults/main.yml`

##  Dependencies

Jinja `combine` filter - contained in Ansible 2.0.

##  Example Playbook

    - hosts: all
      roles:
        - role: postgresql

## License

-   Code released under [MIT](https://github.com/pantarei/ansible-role-postgresql/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

### Author Information

- [Veros Kaplan](https://github.com/verosk/)
-  Based on work of [Wong Hoi Sing Edison](https://github.com/hswong3i)

