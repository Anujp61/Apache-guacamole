# Apache-guacamole

## Apache Guacamole is a free and open-source cross-platform Remote Desktop Gateway maintained by the Apache Software Foundation. It allows a user to take control of a remote computer or virtual machine via a web browser. The server runs on most Linux distributions and the client runs on any modern web browser.
### Installation Procedure of Apache guacamole 
> First we have to install some dependencies for Apache :
```
apt install -y libcairo2-dev
apt install -y libjpeg-turbo8-dev
apt install -y libpng12-dev
apt install -y libtool-bin
apt install -y libossp-uuid-dev 
apt install -y libavcodec-dev
apt install -y libavformat-dev
apt install -y libavutil-dev
apt install -y libswscale-dev
apt install -y freerdp2-dev
apt install -y libpango1.0-dev
apt install -y libssh2-1-dev
apt install -y libtelnet-dev
apt install -y libvncserver-dev
apt install -y libwebsockets-dev
apt install -y libpulse-dev
apt install -y libssl-dev
apt install -y libwebp-dev
apt install -y aptitude
aptitude install libssl-dev
apt install -y libwebsockets-dev

```
> Now download the file the Apache Guacamole :
```

wget https://git.io/fxZq5 -O guac-install.sh
```

> Make it Executable : 
```
chmod +x guac-install.sh
```
> Run it as root :
```
./guac-install.sh
```

> Below is the image where some commands are given while installation :

