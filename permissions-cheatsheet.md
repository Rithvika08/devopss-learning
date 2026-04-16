# Permissions Cheatsheet

## chmod (Numeric)

| Number | Permission |
|--------|-----------|
| 7 | rwx |
| 6 | rw- |
| 5 | r-x |
| 4 | r-- |
| 0 | --- |

Example:
chmod 755 file.sh

## chmod (Symbolic)

u = user  
g = group  
o = others  

Examples:
chmod u+x file.sh
chmod g-w file.sh

## chown

Change owner:
sudo chown user file.txt

## chgrp

Change group:
sudo chgrp group file.txt
