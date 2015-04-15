# Packer templates for FreeBSD

## FreeBSD versions

* 10.1
* 9.3

## build

### amd64 (x86\_64,x64x)

```sh
packer build packer/FreeBSD-10.1-RELEASE-amd64.json
```

### i386

```sh
packer build packer/FreeBSD-10.1-RELEASE-i386.json
```

## add vagrant box

### amd64 (x86\_64,x64x)

```sh
vagrant box add hnakamur/freebsd-10.1-amd64 builds/freebsd-10.1-amd64.box
```

### i386

```sh
vagrant box add hnakamur/freebsd-10.1-i386 builds/freebsd-10.1-i386.box
```


## start vagrant VM

### amd64 (x86\_64,x64x)

```sh
cd vagrant/10.1-amd64
vagrant up
```

### i386

```sh
cd vagrant/10.1-i386
vagrant up
```
