# Git Remote

## Questions

1. how to create ssh key in you local machine?
```ssh-keygen -t rsa -b 4096 -C "nadim.ice.nstu@gmail.com"```

2. how to add ssh key to your github account?

### check connection 
```
PS C:\Users\ASUS> cd $HOME\.ssh
PS C:\Users\ASUS\.ssh> dir
 Directory: C:\Users\ASUS\.ssh

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         3/16/2025  12:33 PM           3389 id_rsa
-a----         3/16/2025  12:33 PM            751 id_rsa.pub
-a----          3/9/2025  12:55 PM            840 known_hosts
-a----          3/9/2025  12:55 PM             96 known_hosts.old

PS C:\Users\ASUS\.ssh> ssh -T git@github.com
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
Hi aa-nadim! You've successfully authenticated, but GitHub does not provide shell access.
PS C:\Users\ASUS\.ssh>
```