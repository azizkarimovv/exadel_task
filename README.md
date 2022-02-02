``SSH troubleshooting``
* first of all you should be sure that ssh_server is working correctly. 
* then, you should have correct `private_key` to access to the server. The permission should be `read-only`. 
* the keypair should exist, that means the pair(`public_key`) should exist in server in right place, where sshd server should check it (e.g. authorized_keys)
* when you are accessing to the server via ssh, you have to write right command, it means you need to specify absoulute path to `private_key`, need to specify  `ssh_port`. Finally, `user` and `ip_address` should be exact the same as the servers'.

``Task related to process list is in processes.sh file``