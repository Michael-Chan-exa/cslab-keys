# cslab keys

## Purpose
- remove password auth on important lab boxes to prevent taking down a simulated production environment
  - 192.168.150.39 (DL)
  - 192.168.150.37 (AA)

## Procedure
- cs members will need to add their computer's SSH key to the `authorized_keys` file here
- contact the cslab maintainer (kenneth) if you require any assistance setting this up

## Generating and installing your own ssh key
- if you do not already have one, run `ssh-keygen`. by default, this writes your public key to `~/.ssh/id_rsa.pub`
- add the contents of this file to the `authorized_keys` file in this repo
- ~~when there is a new commit on this branch, the keys will be deployed automatically~~ 
  - kenneth working on this
