# NOTE

This is clone of https://github.com/atmoz/sftp.

Changes:
- ssh server key is taken from /run/secrets/ssh_host_rsa_key so you can use docker swarm secret
    - ed25519_key (it didn't load for some reason)
- ssh key generation was removed
