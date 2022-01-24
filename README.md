# vsphere_harden

This script is a work in progress, but is intended to harden vcenter and esxi following guidelines provided by the IRS

I left an Example-All.yml file to show how the variables should be set, I recommend if you use plain text in that file to encrypt the file using the ansible-vault commmand or use some other means of keeping your secrets.

I separated the steps into roles so that it would be easy to adapt and reuse. 
