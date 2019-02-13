# centos-jdk-devel

A pretty simple Base Docker Image for CentOS

built

```text
FROM centos:latest
```

plus

```text
yum update
```

and some basic tools via yum:


```text
- java-1.8.0-openjdk
- git
- bzip2
- unzip
- wget
```

then a

```text
yum clean all
```

that's it.
