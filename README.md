# SSH Message

![motd](motd.png)

## Use

1. Allow print motd in `/etc/ssh/sshd_config`: `PrintMotd yes`.
2. Create a symbolic link from `/var/run/motd` to `/etc/motd`.
3. `sudo chmod 755 /etc/update-motd.d/00-example`
4. Use `sudo update-motd` or ` run-parts /etc/update-motd.d` to preview.

## Requirements

  * update-motd
  * figlet

## References

1. [yboetz/motd](https://github.com/yboetz/motd)