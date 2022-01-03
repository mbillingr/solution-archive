# Conda does not work because of certificate problems

## Error Message
TODO

## Cause
Corporate proxy

## Workaround
```
conda config --set ssl_verify false
```
Obviously, that's dangerous but sometimes we need a quick fix.

## Solution (Linux, Workplace specific)
1. Get CATO certificates from https://cc2.catonetworks.com/certificates
2. See https://askubuntu.com/a/94861 how to convert & install certificates
