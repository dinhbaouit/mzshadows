# MZShadows - Monitor socket traffic 
## Set Up

###Client Side:
1. Download https://shadowsocks.org/en/download/clients.html
2. Run with RC4-MD5 mode, password: lalahihi, port: 1080

###Server Side
```$ git clone https://github.com/dinhbaouit/mzshadows.git```
```$ cd mzshadows```
Default run
```$ ./run.sh```
Custum run
```$ python sockserver -p [port] -k [password] -m [encrypt algorithm]```

## Demo

 ![Tux, the Linux mascot](/assets/images/demo.png)
