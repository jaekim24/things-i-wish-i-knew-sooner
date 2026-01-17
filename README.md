## Need internet on your devices but have limited hotspot data?
Use PairVPN.
Your phone needs a hotspot for this to work. 
Download PairVPN on your phone and laptop (or any device that can download pairVPN)
Youre phone will be the server and your devices are the client.
It works by routing the traffic from your device to your phone and into the pairVPN in your phone.
So it looks like the data is being used the on the app so it doesnt look like its being used on a hotspot.

if pairVPN wont connect turn on airplane mode and turn it off now it'll work 

YOU CAN USE PAIRVPN AND TAILSCALE TOGETHER

some context my laptop is the pairvpn client my iphone is the pairVPN server. on the laptop turn on tailscale but have exit node disabled. on iphone start pairVPN. on laptop start pairVPN. 

idk how but im still able to ssh to my home network even though i dont have exit node on. my exit node is an apple tv at home. 

## Want to connect to your home network but dont want to port forward?
Use tailscale.
Have a device in your home network to run as a exit node so users outside of the network can use it to get to your home network.
