# Utility Commands

## Disable touchscreen (annoying)
```
Add to ~/.profile to auto apply after reboots: 
xinput | grep 'ELAN Touchscreen' | grep -Po 'id=\d+' | cut -d= -f2 | xargs xinput disable
```
