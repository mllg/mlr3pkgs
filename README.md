# mlr3pkgs
Meta package with most mlr3 packages as submodules

Initialize:
```bash
git submodule update --jobs 4 --init --recursive
```

Update all submodules:
```bash
git submodule foreach git pull origin master
```

Commit in all submodules:

```bash
git submodule foreach 'git commit -a -m "<msg>"'
```

Push in all submodules
```bash
git push --recurse-submodules=on-demand
```
