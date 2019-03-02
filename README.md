# suricata-tls-ciphersuites
Suricata TLS Cipher Suites Rules

Just a small compilation of rules i used for a passive SSL/TLS audit. The required `suricata.yml` config used where:

```
- tls:
    extended: yes

- tls-log:
    enabled: yes
    filename: tls.log
    append: yes
    extended: yes
    filetype: regular

- tls-store:
    enabled: yes
    certs-log-dir: certs
```
