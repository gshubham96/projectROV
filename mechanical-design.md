# Mechanical Design

Let me just start by saying that I do not have the best hand when it comes to 3D modelling but comparing with my earlier attempts, I am glad to say that I am getting better. :\)

Below you'll find some rudimentary design drafts for the proposed ROV. Since the CAD drawing in itself is not sufficient to get my idea through, I am writing how I plan to implement some cricital components of the ROV.

1. **Hull:** A IP68 rated Pelican or similar case will act as the primary hull. These cases are rated to be immersed underwater and hence should require little modifications for conversion to a functional ROV. They also have the advantage of being robust and hence can handle a dgree of abuse. They are avaible virtually everywhere and are also easy to ship through any of the three means of shipping. The downside includes assymetrical weight distribution and excessive weight & bouyancy. Hence care needs to be given to make intelligent use of space to minimize case size and acheive a uniform weight distribution.
2. **Underwater Connectors: **Pneumatic fittings with pneumatic air hose or a fibre-reinforced plastic hose with brass nipple and hose clamps acts as an reliable albeit a little annoying connection interfaces.
3. **Propulsion:** A custom thruster assemble is proposed consisting of two M100/M200 motors by BlueRobotics and 3-dof fins to give 5-dof to the ROV i.e. heading, pitch, roll, surge. The assembly would effictively be utilizing the principle of Jet propulsion for motion. 
4. **Front Depth control Assembly: **Thrusters are probably the most expensive components of the AUV but still the ability for the AUV to hover is absolutely necessary for any resonable problem. I see two solutions to this problem
   1. Front Thruster: Add one/two depth thrusters with a positively buyant design to mantain a constant depth, heading.
   2. Emergency Bouyant Release device: Developing a nuetral-bouyant design with a solution to change the bouyancy of the ROV in case of a power failure. I am assuming that the main propulsion assemby should be able to provide stability to the vehicle scenario.
5. **Glass window: **I am working on some sort of 3D printed+metal bracket solution to add a glasss window in the Case itself to provide a quick view of the inside and give access to a camera to record photo/video. Alternatively, a seperate camera assembly can be designed to support the major action cams/webcams in the market right now, The latter offers a more reliable and a robust approach but messes big time with the dynamics of the vehicle.

  It is recommended to have a ROV design that utilizes advance prototyping machines accesbile to hobbyist such as 3D printers/Laser Cut/CNC Routers but at the same time, absence of it should not thwart ROV build

![](/projectROV1.jpg)Figure 1: View of Primary Thruster Assemble, and placement of various ROV components

![](/projectROV2.jpg)Figure 2: 

![](/projectROV3.jpg)Fig 3:

