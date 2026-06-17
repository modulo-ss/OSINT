First read the report and examine the pcap file.

And then extract the keywords from the report : communicating through anonymous messages, and codenames etc (This gives us an idea to look into http and dns)

And then we load the pcap file into Wireshark with filter : dns contains "http"

We then find a packet with a http link to a pastebin : https://pastebin.com/raw/U7zb8Kyh

Entering the link into the browser gives us the flag : https://bit.ly/3qyrf7t

https://bit.ly/3qyrf7t
