# ansible.yml
follow structure
dipudeeprock@ubuntu:~$ tree ansible
ansible
├── inventory
│   └── hosts
└── playbooks
    ├── roles
    │   ├── maven
    │   │   └── tasks
    │   │       └── main.yml (maven installisation direction)
    │   └── tomcat
    │       ├── tasks
    │       │   └── main.yml  (tomcat installisation direction)
    │       └── templates
    │           └── tomcat.service.j2 (configuration of tomcat)
    └── setup-tomcat-maven.yml (run roles in host machine and java path set)

    www.yamllint.com for indentation check
    sudo systemctl daemon-reload
    sudo systemctl restart tomcat
