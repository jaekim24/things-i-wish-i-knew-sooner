## Need internet on your devices but have limited hotspot data?
Use PairVPN.
Your phone needs a hotspot for this to work. 
Download PairVPN on your phone and laptop (or any device that can download pairVPN)
Youre phone will be the server and your devices are the client.
It works by routing the traffic from your device to your phone and into the pairVPN in your phone.
So it looks like the data is being used the on the app so it doesnt look like its being used on a hotspot.

## Want to connect to your home network but dont want to port forward?
Use tailscale.
Have a device in your home network to run as a exit node so users outside of the network can use it to get to your home network.

## you can use tailscale and pairvpn together
1. on iphone turn on tailscale but disable exit node
2. turn on pairvpn on iphone (server) and laptop (client) and connect
3. on iphone go to tailscale and enable exit node and select the exit node you want. 

