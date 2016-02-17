# Basic tcpdump usage

tcpdump prints out a description of packets on a network interface that match the boolean expression. It was useful to keep track of a whether proxied requests from one service to another were being sent properly.

Example usage:

* Listen to all network requests on a machine - `sudo tcpdump -i any`
* Listen to all network requests on a specific port -`sudo tcpdump -i any port 8080`
* Listen to all eth0 requests on a machine - `sudo tcpdump -i eth0`

