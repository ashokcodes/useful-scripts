## Find disk space that's being used
```
du -cha --max-depth=1 /var | grep -E "M|G"
```
