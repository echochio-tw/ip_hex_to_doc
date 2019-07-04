# ip_hex_to_doc
python

```
#input 0200A8C0
import socket,struct
socket.inet_ntoa(struct.pack("<L", int("0200A8C0",16)))
```
