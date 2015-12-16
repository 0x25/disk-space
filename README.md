# disk-space

bash command line utility to see files/folders disk usage  
add it to a $PATH folder  

# Exemple

```
ds -h
Return the size of folder/file in current dir
Option:
 -g Giga
 -m Mega
 -k Kilo
 -o other
 -h for help
```

```
ds
-h for show option
file/folder > G
1,4G	.


file/folder > M
512M	./opendocument.dd
462M	./recover
423M	./output


file/folder > K
56K	./all.txt



other
0	./file

```

```
ds -g
file/folder > G
1,4G	./forensic
1,4G	.

```
