# SSH
cat ~/.ssh/config
```
Host su
  HostName github.com
  User git
  IdentityFile ~/.ssh/id_rsa
  IdentitiesOnly yes
```
git remote set-url origin git@su:sky-unlimited-us/portal.git
git pull
