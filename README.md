# Instax
## Author: github.com/dhasirar
## IG: instagram.com/dhasirar
### Don't copy this code without give me the credits, nerd! 
Instax is an Script to perform multi-threaded brute force attack against Instagram, this script can bypass login limiting and it can test infinite number of passwords with a rate of +400 passwords/min using 20 threads.

## Legal disclaimer:
Usage of Instax for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program 

![insta](https://user-images.githubusercontent.com/34893261/37858917-a6f23ae2-2eea-11e8-9f58-9a688390cfb0.png)

### Features
- Multi-thread (400 pass/min, 20 threads)
- Save/Resume sessions
- Anonymous attack through TOR
- Check valid usernames
- Default password list (best +39k 8 letters)
- Check and Install all dependencies

### Usage:
```
git clone https://github.com/dhasirar/instax.git
cd instax
chmod +x instax.sh
service tor start
sudo ./instax.sh
```

### Install requirements (Curl, Tor, Openssl):

```
chmod +x install.sh
sudo ./install.sh
```

### How it works?

Script uses an Android ApkSignature to perform authentication in addition using TOR and rotating the ip address to avoid blocking. 

### Donate!
Support the authors:
https://paypal.me/dhasirar
