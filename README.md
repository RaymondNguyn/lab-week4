# lab-week4
Raymond Nguyen<br />
Aaron Dimatulac<br />
Markus Matsumoto<br />
---

## Initial Set-up
The first step of this lab involves creating a new ssh key in our linux enviroment. To do that we have to run the following command `ssh-keygen -t ed25519`. It will then prompt you to enter where and what you want the key to be stored and called.

We then download the cloud-config.yaml file provided by the instructor. 
in the .yaml file we then fill in the `ssh-authorized-keys:` section with the content of our public key we just generated. After we add the following lines to add packages to our cloud-config.yaml
```
packages:
  -nginx
  -nmap
```
