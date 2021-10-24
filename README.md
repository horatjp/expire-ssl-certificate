# Get SSL certificate expiration date

Use the openssl command to get the expiration date of the SSL certificate.

## Installation

```bash
curl -L https://raw.githubusercontent.com/horatjp/expire-ssl-certificate/master/expire-ssl-certificate -o /usr/local/bin/expire-ssl-certificate
chmod +x /usr/local/bin/expire-ssl-certificate
```

## Usage

```bash
expire-ssl-certificate google.com
```

Date Format
```bash
expire-ssl-certificate -f +%Y/%m/%d google.com
```

Day left
```bash
expire-ssl-certificate -d google.com
```
