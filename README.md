# CoreLayer Tool Suite
## Introduction

Public downloads coming soon!<br>For more information, reach out to info@corelayer.eu !

## Configuration
### Registry

```yaml ```

#### Encrypting the registry

```sh
REGMAN_ENC=<encryption_key> ./regman encrypt
```

### TLS Certificate Manager

```yaml ```

#### Requesting a new certifcate using ACME

```sh
TLSMAN_ENC=<encryption_key> ./tlsman acme request --certificate <certificate_name>
```