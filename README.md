## Get openjdk debs
```sh
$ sudo apt-get install -y --print-uris openjdk-8-jre | grep http
```

```sh
$ bazel run //:my_image
$ docker run -it bazel:my_image
```
