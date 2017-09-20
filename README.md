# build-conductors

Provisions a RHEL7 VM with Docker, Ansible Container and scanning bits:

```
$ ansible-playbook provision.yml --ask-vault-pass
```

On the VM do the following:

- Clone this repo
- Run: `ansible-playbook build-conductor.yml`

