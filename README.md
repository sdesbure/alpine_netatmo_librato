alpine_netatmo_librato
======

netatmo_librato - https://github.com/sdesbure/netatmo_librato

Latest netatmo_librato git release.

**Pull image**

```
docker pull sdesbure/alpine_netatmo_librato
```

**Run container**

```
docker run -d --name=<container name> -v <path for config files>:/config sdesbure/alpine_netatmo_librato
```

Please replace all user variables in the above command defined by <> with the correct values.

per default, the script will use /config/secret.yml so provision it before launch or it will fail

