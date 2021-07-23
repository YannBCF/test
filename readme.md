TEST v0.0.1

# Update sub modules
```
git submodule foreach update --recursive --remote
```

.gitmodules
```
[submodule "my/module"]
	path = my/module
	branch = master
```