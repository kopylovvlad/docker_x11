
## MacOS set up

```bash
# Set your Mac IP address
IP=$(/usr/sbin/ipconfig getifaddr en0)

# Allow connections from Mac to XQuartz
/opt/X11/bin/xhost + "$IP"
```
