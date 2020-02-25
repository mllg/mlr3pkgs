# mlr3pkgs
Meta package with most mlr3 packages as submodules

Update all submodules:
```bash
git pull --recurse-submodules
git submodule update --remote
```

Commit in all submodules:

```bash
git submodule foreach 'git commit -a -m "<msg>"'
```

Push in all submodules
```bash
git push --recurse-submodules=on-demand
```
