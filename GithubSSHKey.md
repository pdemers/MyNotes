# Steps to create SSH key pair for Github:

ssh-keygen -t rsa -C "Pete-Home-Win11"  
Generating public/private rsa key pair.  
Enter file in which to save the key (C:\\Users\\fishhead/.ssh/id_rsa): Pete-Home-Win11  
Enter passphrase (empty for no passphrase):  
Enter same passphrase again:  
Your identification has been saved in Pete-Home-Win11  
Your public key has been saved in Pete-Home-Win11.pub  
The key fingerprint is:  
SHA256:hi0OwZ2f/giZjjpHncQZPg+2gd9BV6b5rg0NtzMVIeQ Pete-Home-Win11  
The key's randomart image is:  
\+---[RSA 3072]----+  
\| o= . \|  
\| . .... .= . . \|  
\| o+o+ .o E . \|  
\| ..X+.. . . \|  
\| .=oOS.. o . \|  
\| .o=\*o = o \|  
\| . = . . \* \|  
\| . .o . o + o \|  
\| .+. . . o . \|  
\+----[SHA256]-----+  

## Edit Config File

PS C:\\Users\\fishhead\\.ssh\> notepad .\\config

## Add to the top of the File:

IdentityFile \~/.ssh/Pete-Home-Win11
