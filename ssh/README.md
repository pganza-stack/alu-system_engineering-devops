# SSH

Connecting to a remote server with SSH and an RSA key pair.

- 0-use_a_private_key: connects to my server as ubuntu with the private key ~/.ssh/school
- 1-create_ssh_key_pair: creates a 4096-bit RSA key pair named school with the passphrase betty
- 2-ssh_config: SSH client configuration that uses ~/.ssh/school and refuses password login
