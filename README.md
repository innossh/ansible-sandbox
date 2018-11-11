# ansible-sandbox

Let's try to run some example playbooks.

```console
$ ansible-playbook -i hosts.ini playbook.example-local.yml
```

```console
$ docker-compose up -d
$ ansible-playbook -i hosts.ini playbook.example-container.yml -e "log_dir=/tmp"
$ docker-compose stop && docker-compose rm -f
```
