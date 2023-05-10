# Github Practice ( wmad101 a20 )

A simple github practice ( wmad101 a20 )

## Configure SSH Keys

```bash
$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

## Make config file

```
# John Doe <username> Github Account
Host github.com-<username>
HostName github.com
User git
IdentityFile ~/.ssh/id_rsa
```