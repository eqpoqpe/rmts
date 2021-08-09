# rmts
A script tool for trash for 'rm'

```bash
case "${arg%%=*}" in
    "-b" | "--local_bin") bin=${arg#*=};;
    "-t" | "--local_trash") trash=${arg#*=};;
    "-s" | "--max_size") max_size=${arg#*=};;
esac
```
