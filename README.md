# First Project 

this is my first mac project.

## Directions for Creating a Key in Shell 

- go into _first-project_
- type `ssh-keygen -t rsa`
- continue typing enter until command prompt returns
- this will create a new SSH key pair at `~/.ssh/id_rsa`
- type `cd ~/.ssh`
- then `ls`
- copy the contents of `~/.ssh/id_rsa.pub` by using 
  - `cat id_rsa.pub`
  - copy the public key that starts with ssh...
- go to https://github.com/settings/keys 
- click on "New SSH Key" button, paste pubkey into GitHub
