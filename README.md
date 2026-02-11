ansible-wordpress-platform/
├── inventories/
│   ├── prod/
│   │   ├── hosts.ini
│   │   └── group_vars/
│   └── staging/
│       ├── hosts.ini
│       └── group_vars/
├── playbooks/
│   ├── bootstrap.yml
│   ├── docker.yml
│   ├── caddy.yml
│   └── wordpress.yml
├── roles/
│   ├── common/
│   ├── ssh_hardening/
│   ├── firewall/
│   ├── docker/
│   ├── caddy/
│   └── wordpress_site/
└── README.md
