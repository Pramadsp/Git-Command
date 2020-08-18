### Initialization
```git
git init
```

### Add file
```git
git add filename or git add . (to all file)
git commit -m "commit name"
```

### Add url
```git
git remote add origin (copas url git)
git remote -v // check available remote url
```

### Upload local -> remote
```git
git push -u origin master
```

### Pull revision
```git
git fetch -u origin master (hold)
git pull -u origin master (auto merge)
```

### Switch branch
```git
git checkout master
```

### Merge remote -> lokal
```git
git merge origin/master (remote -> lokal)
```
### Download 
```git
git clone (url)
```

### History
```git
git log --oneline
```

### Preview changes
```git
git diff 
```

### Update project hasil fork
#### Tambah repositori asal, dinamain "upstream" :
```git
git remote add upstream https://github.com/whoever/whatever.git
```
#### Ngambil semua update dari repositori asal, contoh upstream/master :
```git
git fetch upstream
```
#### Pastiin lagi di branch master repositori lokal :
```git
git checkout master
```
#### Nulis ulang branch master jadi histori commit yang gk ada di upstream/master jadi ada di branch local lain :
```git
git rebase upstream/master
```
