# Tunnel

# Overview

- [Overview](#overview)
- [Sample](#sample)

Create an ssh tunnel to a remote host. This is useful for accessing a remote host
while you are on your company's network. You can use this to access a remote
host that is behind a firewall. It really is only a wrapper around

```bash
ssh 192.168.1.1 -N -L 3389:192.168.1.93:3389
```

because I'm lazy.

# Sample

tunnel to 192.168.1.93
