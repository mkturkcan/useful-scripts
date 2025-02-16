# Potentially Useful Scripts and Commands

I've noticed that sometimes I can't recall a useful command and have to Google it. This is a repository of such commands.

## Bash Scripts


### Sorted Files by Size

du -h --max-depth=1 | sort -hr

### Things to Remember

### Disk Space Issues:

Check ~/.local folder.
### Extend Disk
```bash
growpart /dev/sda 1
resize2fs /dev/sda1
df -h /dev/sda1
```