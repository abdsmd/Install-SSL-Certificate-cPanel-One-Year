# Install-SSL-Certificate-cPanel-One-Year
Install SSL Certificate cPanel One Year

# Enable SSH Access, then Connect SSH Terminal

```curl https://get.acme.sh | sh```
```.acme.sh/acme.sh  --register-account  -m email@domain.com --server zerossl```
```pwd```
```.acme.sh/acme.sh --debug --issue -d domain.tld -d www.domain.tld -w /home/userfolder/public_html/```


Goto SSL/TLS then paste 2 file 
In Certificate: (CRT) Section put the file ```/home/userfolder/.acme/domain.tld/domain.tld.cer```
In Private Key (KEY) Section put the file ```/home/userfolder/.acme/domain.tld/domain.tld.key```

