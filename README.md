# CVE-2024-4577

Tested with the help of [@Rijaba1](https://www.twitch.tv/rijaba1).

PHP CGI Argument Injection (CVE-2024-4577) Remote Code Execution PoC
Discovered by: Orange Tsai (@orange_8361) of DEVCORE (@d3vc0r3)

Based on [Tenable](https://www.tenable.com/blog/cve-2024-4577-proof-of-concept-available-for-php-cgi-argument-injection-vulnerability)

Vulnerability Info:  
[Español](https://www.incibe.es/incibe-cert/alerta-temprana/vulnerabilidades/cve-2024-4577)
[English](https://cve.mitre.org/cgi-bin/cvename.cgi?name=2024-4577)


## USAGE

- For testing if vulnerable:

```
CVE-2024-4577_nc.sh <URL>
```

- For RCE:

```
CVE-2024-4577_nc.sh <URL> <IP> <PORT>
```

## INSTALL

```
git clone https://github.com/PatxaSec/CVE_Payloads.git
```

```
cd CVE_Payloads
```

```
chmod +x CVE-2024-4577_nc.sh
```

