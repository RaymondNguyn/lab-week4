# lab-week4
Raymond Nguyen<br />
Aaron Dimatulac<br />
Markus Matsumoto<br />
---

## Initial Set-up
The first step of this lab involves creating a new ssh key in our linux enviroment. To do that we have to run the following command `ssh-keygen -t ed25519`. It will then prompt you to enter where and what you want the key to be stored and called.

We then download the cloud-config.yaml file provided by the instructor. 
in the .yaml file we then fill in the `ssh-authorized-keys:` section with out public key perferably with `export NAMEKEY="content of ssh"`. We then edit the .yaml and add the following lines of code:

```
packages:
  -nginx
  -nmap
```
