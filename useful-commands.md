## Disable Domain Translation 
Global config mode: 
```
no ip domain lookup
```
# SSH
### Change Timeout
```
line vty 0 15
exec-timeout 0 0
```

### Increase Command History 
``` 
line vty 0 15
history size 30
```

### Disable Logging Popup 
```
line vty 0 15
logging synchronous
```

# Console Port

```
line console 0
exec-timeout 0 0
history size 30
logging synchronous
```