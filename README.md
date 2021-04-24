# VexTab 3.0 - practicing guitar patched

This is a **patched** version of vexflow for https://github.com/jzohrab/practicing-guitar.

It is based off of `upstream/master`.

```
$ git remote -v | grep upstream
upstream	git@github.com:0xfe/vextab.git (fetch)
upstream	git@github.com:0xfe/vextab.git (push)
```

## Patches applied (divergence from upstream)

Note the shas may not be valid, depending on rebasing etc, but the content is good.

```
git log upstream/master..HEAD --pretty=format:"* %as - %s" --reverse
```

```
* 2021-04-24 - Change README for patched branch.
```