##Problem:##

How do the controls work, and what do does each one do?

##Solution:##

####Steering:####

Steering will be achieved through thrust vectoring. Thrust vectoring is
something even helicopters do nowadays to retain stability and
maneuverability. Each thruster will be able to move about its own axis
as it will be placed within two servos which allow movement in two
planes. A fuel distribution system that makes use of valves will be used
to determine the thrust each thruster exerts. This system is also shared
by planes on Earth. Movement will be controlled by a joystick. For extra
stability and reliability the thruster-arms are attached to the belt
previously mentioned.

So if you’re an astronaut: Pushing the joystick forward takes you
forward, pushing it left takes you left, right takes you right and
pulling it backwards takes you backwards. Simple.

###Navigation:####

Since there is hardly any atmosphere on Mars, the stars can be seen and
used as reference points for navigation. Moreover, Mars has weak
magnetic field so other options such as a compass are not available.
During the day, instead of using the stars you can navigate using the
position of the sun. Using a solar filter you can also distinguish the
stars even during the day.

Another option would be to use a series of beacons (that work in all
weather conditions on Mars) to map out the area the network covers. Due
to the minimal atmosphere of Mars, the beacon’s coverage will be much
greater to what it would be on Earth.
Due to the fact that the station and beacons will have a constant distance between them, confirmation pulses wont have to be sent constantly.
A problem emerges now however. the relative distance of the jetpack and it's angle will not always be the same, as the jetpack moves around. Thankfully, the Doppler Effect can help here. In the beggining, the jetpack will be sending a constant electromagnetic wave(Radio Waaves etc.) in all directions. Such systems are used in telecommunications on Earth. The obvious reason for choosing said electromagnetic waves is the fact that they travel in vacuum, and since Mars' atmosphere is so thin they're the most suitable. As said wave now progresses in a circular pattern it will reach the point of the beacon, whereas the jetpack will be perpendicular to the tangent of the circle at that point and moment. Moreover, the radius of that circle is the distance of the (receiver)beacon from the jetpack(source). By applying the Doppler Effect we can know whether the jet pack is approaching or moving away from the beacon. If the source(jetpack) is approaching the receiver(beacon) then the beacon will receive an increased frequency from the original frequency of the source. If the source is moving away from the receiver then the receiver would receive a decreased frequency than the original frequency of the source. Using the wave formulae Δf = vλ/c we can calculate the speed (v) and distance the jetpack has travelled. Using this information we can create a map relative to the base and the beacons. This system will also allow us to plot a map of the area explored by the astronaut compared to the whole map by cross-referencing.
