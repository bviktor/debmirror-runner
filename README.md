# debmirror-runner

Script for easily running debmirror in various setups without duplicating settings.

```
yum install epel-release
yum install debmirror
```

- Set up `/etc/debmirror.conf` as per the provided file.
- Copy `debmirror-runner` to `/usr/local/bin`.
- Set up your mirror files under `/usr/local/etc/debmirror`. See the provided examples.
