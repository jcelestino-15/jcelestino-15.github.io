---
layout: post
title: "Spring Blog 1 - SSH commands"
date: 2022-02-18 16:15:17 -700
categories: jekyll update
---

## SSH commands
Almost every Unix and Linux operating system has the ssh command. The SSH (Secure Shell) is a network protocol that allows two systems to have a secure remote connection. The ssh command launches the SSH client program, which starts the encrypted connection to the SSH server on a remote machine. The connection is utilized for other purposes as well, such as for terminal access, file transfers, tunneling with other programs, etc.

### Common SSH Commands
Accessing a Remote Server: 

To access a remote server, you need its IP address or name. The command to access is: `ssh 192.168.46.111` or the name: `ssh server.com`

Specify a username:

The user needs to run the command: `ssh username@hostname_or_ip` to specify a different username. For example, `ssh user1@10.0.0.55`

Connect to a non-standard SSH port: 

The default SSH port is 22. To connect using a different port number, you will need to use this command: `ssh -p 2222 server.com`

Creating key pair for public key authentication: 

SSH Keygen generates SSH keys. The key pair improves the security of SSH connections; the pair includes a public and private key. The public key can be shared, but the private key needs to be secured. The key pairs authenticate clients to servers automatically. The command to create a key pair is: `ssh-keygen -t rsa`. 

Copy Public key:

To copy the public key to a server, the command will be from the client: `ssh-copy-id hostname_or_IP`. The key is the file id_rsa.pub created from the keygen utility. 
    
File transfer client with SCP (Copying a File Remotely):

Securely copy files over the SSH using SCP. The command is: `scp fileName user@remotehost:/home/username/destination`

Restart SSH service:

You use the command: `sudo ssh service restart` or `sudo sshd service restart` whenever you make changes to the SSH configuration.

### Here is a list of common SSH command line options: 
![SSH Command Line options](/assets/images/ssh-command-line-options.png)
