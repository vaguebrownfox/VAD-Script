# VAD Script

-   Automate validation of data acquired from Asquire Web-app

#

## Download data from Google cloud bucket

-   using `gsutil` cli

```
> gsutil -m cp -R gs://[ bucket-name ]/[ src-folder-path ] [ local-destination ]
```

```
> gsutil -m cp -R gs://asquire-mox.appspot.com/data0x04_users_vad ./
```
