Download node binary: https://nodejs.org/en/download/

- Unpack the binary to your installation folder, for example, tar zxvf node-v12.16.2-linux-s390x.tar.gz -C /opt.
- Create one file nodejs.sh in /etc/profile.d with following content:
```shell
#!/bin/sh
export PATH=/opt/node-v12.16.2-linux-s390x/bin:$PATH
```
- Restart the session
