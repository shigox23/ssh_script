# ssh_scripts
Scripts to make it easier to generate ssh keys and a ssh config file.

### ssh-gen
It prompts user for email & passcode & keyfile name inputs to generate ssh-key.
Once ssh-key is generated it adds the private key to ssh-agent.

The script also allows one to upload their public key to a remote server.

### ssh-config
Prompts user for general settings (host, host name, port, user, private key)
User can leave a field empty and it will not be written to the config file.

_The private key field uses by default the ~/.ssh directory so one only needs to supply the private key name_

---

Feel free to add the files to /usr/bin and run as a local commands.
