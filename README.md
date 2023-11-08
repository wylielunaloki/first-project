# First Project 

this is my first mac project.

## Directions for Creating a Key in Shell 

- go into _name of Repo_
- type `ssh-keygen -t rsa`
- continue typing enter until command prompt returns
- this will create a new SSH key pair at `~/.ssh/id_rsa`
- type `cd ~/.ssh`
- then `ls`
- copy the contents of `~/.ssh/id_rsa.pub` by using 
  - `cat id_rsa.pub`
  - copy the public key that starts with ssh... To "copy" in vsc terminal, use cont+shift+c and to paste, use cont+shift+v
- go to https://github.com/settings/keys 
- click on "New SSH Key" button, paste pubkey into GitHub
- to add the other key (private key) in terminal, follow directions on Github help. But also, do this--> type   `eval "$(ssh-agent -s)"` then `ssh-add ~/.ssh/id_rsa` (note: Repace 'id_rsa' if I saved the keypair under a new name, which I can do when generating it. 
