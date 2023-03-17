# nat-port-forward

It is easy to add port forwarding via NAT.

In the script setup, you need to define variables inside the file.

Determine the external ip address of the ip inside the local network.

Determine the port on the external ip address and determine the port for forwarding within the network.

$EXT_IP - external IP address

$LOCAL_IP is the internal "fake" address of the machine that needs to be "thrown out" inside the local network.

$PORT_in - The port that will be accessed from the outside and get to the local machine. Port on the WAN side of the interface.

$PORT_out - The port to which traffic is redirected inside the local network. An open port on the local machine.
