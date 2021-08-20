Raspberry Pi
===============


New servers


SSH into the server manually with user & password to store the server into the known hosts

Edit `inventory.yml` on the `new` server and edit the ip address to connect

Then run ansible to install the ssh key

```
playbook new.yml -i inventory.yml
```


Once is configured, can be added to the `inventory.yml` as the host name  