# ssh_script
Scripts to make it easier to generate ssh keys and a config file

### ssh-gen
It prompts user for email & passcode & keyfile name inputs to generate ssh-key.
Once ssh-key is generated it adds the private key to ssh-agent.

The script also allows one to upload their public key to a remote server.

Feel free to add the file to /usr/bin and run ssh-gen as a local command.

### ssh-config
Prompts user for general settings (host, host name, port, user, private key)
User can leave a field empty and it will not be written to the config file

_Private key uses by default the ~/.ssh directory so one must only supply the private key name_
