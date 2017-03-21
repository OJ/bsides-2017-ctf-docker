* This binary challenge was worth `350` points.
* Run `docker-compose up` and then `nc localhost 6379` to connect to the service.
* The `incredis` binary can be found in the current folder.

## Important note

This challenge was set up behind a firewall that does not allow any inbound (other than the listening port) or outbound traffic. The intent here was to give the competitors an interesting exfiltration challenge. Unfortunately doing this just with docker was beyond me. Rather than released a VM, I thought I'd leave it as is and tell you that you if you're going to tackle this with a reverse shell, you're doing it wrong!

See if you can pop the flag without spawning a new shell, or pushing data out through another connection.
