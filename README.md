# Ansible best practices : Alternative layout


This is a lazy way to get [Ansible Alternative Directory Layout](https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html#directory-layout) configured.

Simply clone this repo and start working on your ansible project.

This is what you get:

``` bash
> tree -a

|
├── filter_plugins
├── inventories
│   ├── production
│   │   ├── group_vars
│   │   │   └── atlanta.yml
│   │   ├── hosts
│   │   └── host_vars
│   │       └── .gitignore
│   └── staging
│       ├── group_vars
│       │   └── .gitignore
│       ├── hosts
│       └── host_vars
│           └── .gitignore
├── library
│   └── .gitignore
├── module_utils
│   └── .gitignore
├── README.md
├── roles
│   └── common
│       ├── defaults
│       │   └── main.yml
│       ├── files
│       │   └── .gitignore
│       ├── handlers
│       │   └── main.yml
│       ├── library
│       │   └── .gitignore
│       ├── lookup_plugins
│       │   └── .gitignore
│       ├── meta
│       │   └── main.yml
│       ├── module_utils
│       │   └── .gitignore
│       ├── tasks
│       │   └── main.yml
│       ├── templates
│       │   └── .gitignore
│       └── vars
│           └── main.yml

```
