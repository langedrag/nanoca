# nanoca
Absolute minimal CA based openssl.

## Install

Clone
```bash
git clone https://github.com/langedrag/nanoca
```

Install
```bash
cd nanoca
./ca-init
```

## Use
### Issue certificate

```bash
./ca-issue hostname.example.com
```

### Revoke certificate
```bash
./ca-revoke hostname.example.com
```
### Run OCSP server 
```bash
./ca-ocsp
```
