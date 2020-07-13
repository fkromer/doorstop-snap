# doorstop

Dev notes about testing of snap.

```
$ snapcraft clean
$ snapcraft
$ sudo snap install *.snap --devmode --dangerous
doorstop 2.1.2 installiert
$ /snap/bin/doorstop -V
Doorstop 2.1.2
$ /snap/bin/doorstop create SRD ./reqs/srd
$ /snap/bin/doorstop add SRD
$ test -f reqs/srd/SRD001.yml
$ $?
$ doorstop publish all ./public
$ firefox ./public/index.html
```

