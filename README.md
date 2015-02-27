Linux-dash on busybox container
===============================

#busydash

A 32MB node.js busybox container from hwestphal/nodebox, with linux-dash installed and ran on port 80.

To start using it:

```
# git clone https://github.com/galal-hussein/busydash.git
# docker build -t husseingalal/busydash busydash/
# docker run -d -p 8000:80 hussiengalal/busydash
```
Run at http://localhost:8000

Enjoy !
