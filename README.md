#

## Pre requirements 

This project require some tools installed in your laptop

- git
- vagrant
- virtualbox

if your OS is macos, you can intall brew ( link to brew.sh )

and then install the tools like

- git
macos:
install xcode

linux:
```
apt-get install git
```

| tool | macos | linux |
| ------------- | ------------- | ------------- |
| git | xcode --cli | `apt-get install git`|


## How to use

- clone this repo to your computer

```
git clone https://github.com/kikitux/myweb.git
```

- change directory to the new created directory

```
cd myweb
```

- create the vms with vagrant

```
vagrant up
vagrant status
```


## TODO
- [ ] provision website
- [ ] provision database
- [ ] this readme

## DONE
- [x] multi machine vagrant

