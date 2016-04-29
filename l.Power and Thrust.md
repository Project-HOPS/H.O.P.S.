#Power Output/Input#
---
The hydrogen-oxygen reaction produces water and energy equal to approximately 572kJ which will be used as thrust to exert an upwards force to lift off the driver and the jetpack.

In order for the jetpack to retain a constant height (ΣF = 0 N) it requires the 4 thrusters to exert a constant force, equal to the total weight, vertically. Thereforce to calculate the power required we need to take into consideration the time taken for the trip to a certain location, the force it will exert as well as the distance travelled. 

P = (F*Δx)/Δt

Theoretically, the thrusters will need to share the weight of the jetpack equally, each needing to exert a force of approximately 607.91N(in our case - varies) to maintain a constant height. To either increase or decrease the height the thrusters need more or less power respectively provided by the combustion or a higher rate of combustion. This can be calculated using simple basic physics.


##How would you calculate everything?##

Let me give you an example. Say you need to climb to a height of 3m(B) and then get back down while traveling a horizontal distance of say 14 meters(A to C), in a time of 60 seconds and with an acceleration of 3m/s^2. How much total power would you need?

![alt tag](http://i.imgur.com/bw9koSm.png)

There are 3 points on our diagram that have changes in power output. Those are A,B and C.
While the pilot is moving from A to B, he needs to increase it's thrust both horizontally and vertically.
Hence we're left with a horizontal(Ph) and a vertical(Pv) power output.

###Vertical Power:###
---

1.Pv = F*y/t 		 F = mg + ma = 607.91 + 164.3*a (a = 3 m/s^2) = 1100.81 N

2.Pv = 1100.81*3/t		t = 30s

3.Pv = 1100.81*3/30

4.Pv = 110.08 W

###Horizontal Powe:r###
---

1.Ph = F*x/t		F = m*a (a = 3 m/s^2) = 164.3* 3 = 492.9 N

2.Ph = 492.9*14/t		t = 60s

3.Ph = 492.9*14/60

4.Ph = 115.01 W
***
#####After you've finished calculating the horizontal and vertical components, you can calculate the total Power you need by using the Pythagoras theorem:#####

P total = Ph / cosθ  

P total = Pv / sinθ	

Ph / cosθ = Pv / sinθ    

115.01 / cosθ = 110.08 / sinθ

tanθ = 110.08  / 115.01

θ = 43.75

P Total = 159.2 W

![alt tag](http://i.imgur.com/bcWE1u4.png)

And you now have the total power you need to get from point A to point C, while also ascending to 3m and then descending back to the ground.
