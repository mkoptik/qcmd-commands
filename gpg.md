# GnuPG commands

### Import public key

```
gpg --import <path-to-public-key>
```

### Encrypt file

```
gpg --output <output-file> --encrypt --recipient <email-or-public-key-id>
```

### List keys with keyid

```
gpg --list-keys --keyid-format LONG
```
