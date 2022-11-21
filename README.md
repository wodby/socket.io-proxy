# About

Patched version of https://github.com/stbrenner/socket.io-proxy. A few changes:

- support for wss protocol (just replaces to https)
- always use http connection (even for https endpoints)
- added protocol with a hostname to request path (squid doesn't work if only Host header specified)
