##Problem:##

How do the controls work, and what do does each one do? How will you not get lost?

##Solution:##

####Steering:####

Steering will be achieved through thrust vectoring. Thrust vectoring is
something even helicopters do nowadays to retain stability and
maneuverability. Each thruster will be able to move about its own axis
as it will be placed within two servos which allow movement in two
planes. A fuel distribution system that makes use of valves will be used
to determine how much thrust each thruster exerts. This system is also shared
by planes on Earth for distributing fuel. Thrust vectoring not only helps for maneuverability but also bigger autonomy for the jet pack.
Movement will be controlled by a joystick. A secured button on the joystic kwill start/stop the engine combustion and using a slider you will be able to decrease or increase thrust/flow respectively. For security purposes, an extra putton at the bottom of the joystick will lock ingition button. For extra stability and reliability the thruster-arms are attached to the belt
previously mentioned.

So if you’re an astronaut: Pushing the joystick forward takes you
forward, pushing it left takes you left, right takes you right and
pulling it backwards takes you backwards. Simple.

###Navigation:####
Due to the fact that Mars has weak magnetic field options such as a compass are discarded.

An option would be to use a series of beacons (that work in all
weather conditions on Mars) to map out the area the network covers. Due
to the minimal atmosphere of Mars, the beacon’s coverage will be much
greater to what it would be on Earth.
Due to the fact that the station and beacons will have a constant distance between them, confirmation pulses wont have to be sent constantly.
A problem emerges now however. the relative distance of the jetpack and it's angle will not always be the same, as the jetpack moves around. Thankfully, the Doppler Effect can help here. In the beggining, the jetpack will be sending a constant electromagnetic wave(Radio Waaves etc.) in all directions. Such systems are used in telecommunications on Earth. The obvious reason for choosing said electromagnetic waves is the fact that they travel in vacuum, and since Mars' atmosphere is so thin they're the most suitable. As said wave now progresses in a circular pattern it will reach the point of the beacon, whereas the jetpack will be perpendicular to the tangent of the circle at that point and moment. Moreover, the radius of that circle is the distance of the (receiver)beacon from the jetpack(source). By applying the Doppler Effect we can know whether the jet pack is approaching or moving away from the beacon. If the source(jetpack) is approaching the receiver(beacon) then the beacon will receive an increased frequency from the original frequency of the source. If the source is moving away from the receiver then the receiver would receive a decreased frequency than the original frequency of the source. Using the wave formulae Δf = vλ/c we can calculate the speed (v) and distance the jetpack has travelled. Using this information we can create a map relative to the base and the beacons. This system will also allow us to plot a map of the area explored by the astronaut compared to the whole map by cross-referencing.

In telecommunications the round-trip delay time(RTT) is the time taken for a signel to be sent and the time needed for it to be acknowledged by the receiver. By using this sytem our beacons can locate and find the distance between them and the jetpack, when the signal is received. This is a potentially good way to map the area between beacons before the astronauts travel to the planet. Thus, at first the astronauts will not get lost as easily and have a pasic kind of map before wandering intro a "strange planet". This can also help to form a Local Positioning System(LPS). The way we're going to determine the distance between our beacons and the base station while they're being built is by using multilateration(MLAT), which is a technique based on the measurement of the difference in distance to two known stations, in this case the base and the beacon, by broadcasting signals at known time between them. These are systems currently in use by aircrafts and towers.

![alt tag](http://i.imgur.com/piau5gx.png)

#####Navigation using Stars:#####
What if you haven't built the beacons yet? How are you going to navigate?
The answer is above. Literally. You can use the stars. As you know, the intensity of sun light on Mars is much less than that of Earth, due to the distance of Mars from our sun. Moreover, the atmosphere of Mars is much less polluted and thinner than that of Earths'. So by using 2 or 3 stars as reference points and using the distances between them at night to form hours and days on Mars, as well as an orientation compass by using the patterns stars form we can know where we are relative to our base. Moreover, other interstellar bodies can be used to navigate such as one of the moon of Mars, Phobos. If you're wondering how you're going to navigate using the stars while it's still day, there's a simple solution. Use a solar filter to distinguish the stars even if the sun is up.
