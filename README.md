  # <img src='https://github.com/iits-consulting/otc-auth/blob/main/static/images/iits-2024.svg' width=150/> otc-auth apk-repo 
 This repo contains .apk files built from the [latest version of otc-auth](https://github.com/iits-consulting/otc-auth/releases).

 ## Usage 
 ```bash 
 apk add curl 
 curl -SsL -o /etc/apk/keys/otc-auth.rsa.pub https://iits-consulting.github.io/apk-repo otc-auth.rsa.pub 
 apk add otc-auth --repository='https://iits-consulting.github.io/apk-repo' 
 ```
