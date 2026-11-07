# Reach a remote port locally

Makes the server's port 5432 available on localhost:5432.

```sh
ssh -N -L 5432:localhost:5432 user@host
```
