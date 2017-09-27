# Tether

The two major tether systems I've had a look at are

1. 2-wire ROV Tether by OpenROV + TopSide Interface Boards + Tenda Homeplug Adaptor ~ $155
2. Fathom ROV Tether + Fathom Interface Boards ~ $1600

While the first one has bandwidth limitations, the latter is too expensive to fit into our budget.

I have read several blog posts about testing with fiber optic cable as an ROV tether but unfortunately, no results are posted. Overall, I did feel a negative atmosphere for FO tethers mainly due to them being expensive, delicate and difficult to work with. While this was certainly the case a few years back, I feel the price and availability and tools now available are much cheaper and hence this option can be considered. There still remains the problem of FO being too delicate.

I am planning to solve this by designing adaptors that would be fixed along the FO cable with a kevlar fishing line of sorts. The purpose of adaptors would be two-fold

1. To distribute the weight, Pull/Push force on the tether among itself and the kevlar line
2. To effectively provide a net buoyant tether by having positive buoyancy.

There is still a high probability that an FO tether might fail due to plenty reasons such as bending radius of cable & technical know-how. We can always replace the FO cable with a normal Ethernet Cable but will need to add tether interface to boost the signal for 100+ meters. Another thing to consider is the Co-axial cable. It is relatively strong with a higher range.

I will post an analysis of different types of tether solutions soon![](/assets/tether.png)

Cost Analysis:

100m FO/Eth Cable = $55  
RJ45 - FO Interface = $45\*2=$90  
100m Kevlar Line = $50  
3D Printing = $55  
Total ~ $250  
Budget Target = $200

