## Find disk space that's being used
```
du -cha --max-depth=1 /var | grep -E "M|G"
```

# Find Overall Disk space
```
df -h
```

# Find space used by directory
```
du -sh /home
```

# Truncate File
```
truncate -s 0 ./filename
```


# Grep Stuff

## Search for files above 50M
```
find . -type f -size +50M
```


# Making a node executable
Add `#!/usr/bin/env node` to the top of file

```
mkdir ~/bin
cp script ~/bin
export PATH=$PATH:~/bin
source ~/.bashrc
```
