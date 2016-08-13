# Simple HTTP server

A `C` HTTP server that (kinda) handles `GET` requests in a definitely not sane manner.

It's a prefork server, number of forks is defined by `BACKLOG`.

Again it's no pretty code, but it was fun to implement.

```
gcc ./server-prefork.c -o server-prefork && ./server-prefork
```
