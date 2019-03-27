# http2-nodejs

## 
    Gib Devs meetup

## Generate SSL certificate for localhost
    openssl req -x509 -newkey rsa:2048 -nodes -sha256 -subj '/CN=localhost' -keyout key.pem -out cert.pem
    
    Copy the key.pem and cert.pem files and put under “secret” folder. 