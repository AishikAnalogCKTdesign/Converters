# Converters
DC -DC  Converters and SMPS.

In Electronics there are different types of converters 

1)AC-DC converters 

2)DC-AC converters

3)AC-AC converters

4)DC-DC converters

Here in this topic we are going to discuss DC-DC converters ,their working and why they are called by such names.

Before Starting we will be discussing a very important concept known as the DUTY CYCLE.So what is duty cycle?

The time for which my circuit is activated within my input cycle is known as DUTY CYCLE.PIC1 gives you an idea of the same.)

Now DC - DC converters are of 3 types 

1) Buck converter

2) Boost converter

3) Buck-Boost converter

Let have a discussion on Buck converter(Open the diagram and the explanation in 2 different tabs for better understanding)

From the diagram in Pic2 it is clear that a Buck converter has a switch in series with a input and branched network of Inductor ,Capacitor and a diode with a load.

When the Switch is on there is a sudden change in current which is creating a voltage accross the Inductor(Lenz's Law) and hence at the output the Effective voltage is Vs-VL=Vo and also due to the duty cycle which is always less than 1 the output voltage will be less than the input voltage.

When the switch is off then the effective circuit is the branched circuit of Diode Inductor and Capacitor and the load and as the supply is cut off there is again a sudden change in current hence the inductor will discharge through partially via C and partially via R and through the diode .As the supply is cut off so the charge inside the inductor will decrease as it is dicharging and come to zero and hence the output voltage will be less than the input voltage.In both the modes the output voltage is less than the input voltage hence it is called the BUCK converter or Less converter.

Let have a discussion on Boost converter(Open the diagram and the explanation in 2 different tabs for better understanding)

From the diagram Pic3 the circuitry is clear that the inductor is now in series with the input and the branched circuit consist of the diode the capacitor the load and the switch.

When the Switch is on the Inductor gets charged to Vs and the rest of the cuircuit is deactivated as the switch is now closed as shown in the figure via pink line.Hence my output is equal to my input.So why it is called Boost ,it should increase the voltage right?

Lets see when the switch is off the the branched circuit is on and the current is doubled due to the fact as the Inductor gets discharged as well as the Battery also provides the current .KVL if applied then we get Vs - VL =Vo now VL is negative (Lenz's law) hence the equation becomes Vs + VL =Vo .So my output voltage is greater than that of the input voltage.Hence we call it Boost converter


Let have a discussion on Buck-Boost converter(Open the diagram and the explanation in 2 different tabs for better understanding)

So its a combination of both Buck and Boost converter as we can see from the diagram in Pic4 .Here we have a switch connected with Vs and the branched circuit consist of the inductor ,Diode in reversed biased condition and then a Capacitor and an Resistor.

When the Switch is on the effective circuit is Inductor in series with the Battery.Hence it gets charged to Vs and hence the Vo=Vs.Here also we have the concept of duty cycle upon which my Inductor may or may not get charged upto Vs.Vo/Vin=D/1-D where D is the Duty cycle.

However when the switch is off then as usual there will be a sudden change in current and the inductor will discharge via the capaciator and the diode and there will be continuous  flow of current and hence the voltage accross the load will increase and hence acting as a boost .





