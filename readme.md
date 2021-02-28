# personal portable git 2.30.1.windows.1 
#### setup
add __SSHPRIVATE__ to environment variables<br>
format `c:\\path\\to\\openssh-private`
#### commit without .gitconfig set
```powershell
git -c user.name="crbyxwpzfl" -c user.email=no@mail.given commit -m "test"
```
#### point git to openssh key
```powershell
git -c core.sshCommand="ssh -i %SSHPRIVATE%" clone git@github.com:crbyxwpzfl/various.git
```
# [source from](https://git-scm.com/download/win)
