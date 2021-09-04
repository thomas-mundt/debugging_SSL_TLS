# Debugging of SSL/TLS

- https://www.ssllabs.com/ssltest/analyze.html 
- https://github.com/noxxi/p5-ssl-tools/blob/master/analyze-ssl.pl 
- https://github.com/noxxi/p5-ssl-tools 
- https://github.com/trimstray/htrace.sh/blob/master/README.md 
 

## Using htrace script

```
git clone https://github.com/trimstray/htrace.sh
cd htrace.sh
./setup.sh install

htrace.sh --domain https://example.com
htrace.sh --domain https://google.com --headers

```



## Using OpenSSL

```
openssl s_client -connect www.linoxide.com:443
```


