# Linux-Pass-Reset
Reset your Linux password from external pen drive 
```
(First make linux pen drive and run it live)
```
## How to use?
After running live os, 
open terminal and run following commands
```
>> sudo apt-get install git
```
```
>> git clone https://github.com/engineseller/linux-passreset
```
```
>> cd Linux-Password-Reset
```
```
>> chmod 755 ./linuxPassReset.sh
```
```
>> ./linuxPassReset.sh -r
```
Now you are in system files

## Use passwd command to change password
for changing password of current account
```
>> passwd
```
for changin password of sepcific account
```
>> passwd -u root
```

## NOTE
root user can change password of any account
