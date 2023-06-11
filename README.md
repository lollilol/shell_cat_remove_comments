# shell_remove_comments

### this is a very simple script that lives in your path, which you can pipe to to remove comments.

# Install
- place [remove_comments](remove_comments) in /usr/local/bin/
- make it executable: chmod u+x /usr/local/bin/remove_comments

# Usage:
```bash
$ cat /etc/locale.gen | remove_comments
en_US.UTF-8 UTF-8
```
