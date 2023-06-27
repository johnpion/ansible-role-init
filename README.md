# Ansible Role 'init'

The role do 1st setting for new installation of Debian  
Can do dist-upgrade (:!: be careful :!:)

## system
OS: Debian 10

## fixed issues
```
TASK [init : passwd root] *************************
fatal: [SERVER]: FAILED! => {"msg": "crypt.crypt not supported on Mac OS X/Darwin, install passlib python module. crypt.crypt not supported on Mac OS X/Darwin, install passlib python module"}

# pip3 install passlib   
```
