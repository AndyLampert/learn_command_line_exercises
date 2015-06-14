**What option to ls tells it to output file size in human readable form?**

I use `ls -lh` a lot for this. The `l` is long format, which is nice because it shows the permissions, owner, file size, etc. Adding `-h` adds a unit to the filesize, making it much more human readable.

**Is there a case insensitive option to grep?**
Yep! It's `--ignore-case` or `-i`. I confirmed by adding some banannas in a .txt file. 

`$ grep "bananna" ex19.txt`
```
=> bananna
bananna
```

`$ grep -i "bananna" ex19.txt`
```
=> bananna
bananna
Bananna
Bananna
```

**What does the -r and -f options to rm do exactly?**
`-f` tries to remove files and directories. 
`-r` removes things recursively, meaning everything in that folder will also be deleted.

**What does the ifconfig command do?**
It looks like it's a utility for network interface configuration.
