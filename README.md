# Install and Configure Postfix as Send-Only with enforced TLS Encryption on Ubuntu 18.04 LTS

[![Postfix Version](https://img.shields.io/badge/Postfix-3.3.0-brightgreen.svg)](http://www.postfix.org/)

Code example used in the tutorial <br />
[Install and Configure Postfix as Send-Only with enforced TLS Encryption on Ubuntu 18.04 LTS](https://sebastian-stemmer.com/techblog/posts/install-and-configure-postfix-send-only-enforced-tls-encryption-ubuntu-1804-lts/)


Install Postfix

```bash
sudo apt-get install postfix
```

Copy `main.cf` file to

```bash
/etc/postfix/
```

Restart Postfix

```bash
sudo service postfix restart
```
