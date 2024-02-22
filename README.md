# ansible-role-sshd

configure sshd

## Requirements

none

## Variables

1. inventory.ini

```yaml
sshport: "port number"
user: "username of the server"
ssh_private_key_file: "path to private key file"
```

## Dependencies

none

## Example Playbook

`tests/test.yml`

`cd tests` and run the playbook with the following command:

```yaml
ansible-galaxy install -r requirements.yml
ansible-playbook -i inventory.ini test.yml
```

## License

BSD

## Author Information

telegram: [@Qteam1](https://t.me/Qteam1)
