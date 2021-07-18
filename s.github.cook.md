---
id: 4511e8f1-8149-4e13-b737-fd4e79aa3019
title: Cook
desc: ''
updated: 1625328264557
created: 1609285243475
---

### Use multiple keys
- [source](https://gist.github.com/jexchan/2351996)
- additional: https://docs.github.com/en/developers/overview/managing-deploy-keys#using-multiple-repositories-on-one-server

- clone example
```bash
# host entry: github.com-dendrondev
# owner: kevin-dendron-dev
# repo: dendron.vault.private

# clone
git clone git@github.com-dendrondev:kevin-dendron-dev/dendron.vault.private.git

# remote add
git remote add origin git@github.com-dendrondev:kevin-dendron-dev/dendron.vault.private.git
```


### Clone using personal access token
- [source](https://stackoverflow.com/questions/42148841/github-clone-with-oauth-access-token)

```
git clone https://${TOKEN}:x-oauth-basic@github.com/MyUser/MyRepo.git
```
