# login.root
Minimal binary to call 'login -f root'

copy to /bin/

and you can exec it via mingetty / agetty, examples:

```
 mingetty -l /bin/login.root ...
 agetty -l /bin/login.root 115200 /dev/ttyS0 vt100
```
