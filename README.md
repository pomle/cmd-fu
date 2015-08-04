# cmd-fu

#Count lines added to file per 10 seconds
```bash
tail -f access.log | pv -l -i10 -r >/dev/null
```
