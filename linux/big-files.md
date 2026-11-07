# Find big files

Lists files over 100 MB below the current folder.

```sh
find . -type f -size +100M -exec ls -lh {} +
```
