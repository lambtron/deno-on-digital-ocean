# Deploy Deno to Digital Ocean

Create digital ocean account

Install `doctl`

Create private registry which you can store images on

```
doctl registry create <your-private-registry-name>
```

Create SSH key
https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys-on-ubuntu-20-04
and copy the public key.

SSH into your droplet. create a rsa private key. copy the public key to "authorized_keys".
copy the private key. use the private key as the github action private key.

