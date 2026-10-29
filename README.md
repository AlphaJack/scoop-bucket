# Scoop bucket

[Scoop](https://scoop.sh) bucket for my packages.

```pwsh
# install scoop
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression

# add the bucket
scoop bucket add alphajack https://github.com/AlphaJack/scoop-bucket

# install packages
scoop install alphajack/mercurio
scoop install alphajack/rusticlone
```
