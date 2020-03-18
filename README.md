# MZShadows - Monitor socket traffic 
## Introduction
A Socks5 proxy with encryption to bypass internal firewall

## Operation
 ![images](/assets/images/op.png)

## Set Up

### Client Side:
1. Download https://shadowsocks.org/en/download/clients.html
2. Run with RC4-MD5 mode, password: lalahihi, port: 1080

### Server Side
#####
```$ git clone https://github.com/dinhbaouit/mzshadows.git```
#####
```$ cd mzshadows```
#####
Default run
```$ ./run.sh```
#####
Custum run
```$ python sockserver -p [port] -k [password] -m [encrypt algorithm]```

## Demo

 ![images](/assets/images/demo.png)

## Author
dinhbaouit aka 0xd0ff9 (https://twitter.com/Jok3rDb)
