# tdlib-docker

Docker image with precompiled Telegram [tdlib](https://github.com/tdlib/td) library, based on alpine 3.12.

```
COPY --from=superboomer/tdlib /usr/local/include/td /usr/local/include/td
COPY --from=superboomer/tdlib /usr/local/lib/libtd* /usr/local/lib/
```

