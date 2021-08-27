# Unix Commands
### Virtualization 
A technology which allows us to run multiple OS at the same time on a single machine.

### Remotely connecting to a unix/linux box
```
ssh nitesh@192.168.1.101
```
nitesh - username of the remote unix/linux machine
192.168.1.101 - ip address of the remote unix/linux machine

When prompted for password, enter the password for the remote unix/linux machine user.

### Key-based SSH login authentication
#### Generating a key-pair
```
ssh-keygen
```
<pre>
[nitesh@tektutor Fruits]$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key (/home/nitesh/.ssh/id_rsa): 
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /home/nitesh/.ssh/id_rsa.
Your public key has been saved in /home/nitesh/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:WOb1I18WNQC4PcqYhBNEzWepxPaM5EIqXASpTYCUt8w nitesh@tektutor
The key's randomart image is:
+---[RSA 3072]----+
|++=.oo+   o......|
|.o.o o B =     ..|
|oo= + B X +   .  |
|.o.E + X = +   . |
|  .   = S o + o  |
|       o o o +   |
|            .    |
|                 |
|                 |
+----[SHA256]-----+
</pre>

