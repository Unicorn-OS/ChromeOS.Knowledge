interface=mlan0
interface=wlan0

while true; do awk '/mlan0/ {print "Received: " $2/1024 " KB  |  Sent: " $10/1024 " KB"}' /proc/net/dev; sleep 2; done
