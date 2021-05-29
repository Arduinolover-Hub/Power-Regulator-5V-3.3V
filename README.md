# Power-Regulator-5V-3.3V
Power Regulator 5V &amp; 3.3V. Basic circuit with 7805 and 1117/+3.3V

# Main features:
Basic circuit Easy to build
Use 7805 for 5V regulation
Use 1117 +3.3V for this level regulation

# Schematic Diagram
For this circuit and pcb desing we are going to use Altium Designer, which is a very powerfull software of pcb design.
This is kind similar circuit that the Arduino Uno board used for his external power supply. so let's take a look of each part.So firt at all We can supply this pcb with and external source between 6V-18V aproximately, with 9V will be fine. As we can see we connect a diode 1N4004, this is a protection in case that We connect wrongly. After our Protection we can see the chip 7805, very famous and very use,
Now in this part of the circuit We continue with the regulations but with the chip 1117-3.3V, this is the same chip that the Arduino boards use. so we can consider this chip also for anothers projects.

# PCB Layout
Before We continue with the PCB layout, it is important to indicate that You can use any software for PCB Desing, believe me there are many options, even if you use the best software it will not mean that you are the best pcb desinger, so in this case We are going to use the Powefull Altium Designer highly recommended if you want to enter in the pcb design world.

So after We finished and check our schematic circuit We need to switch from schematic to PCB layout. In the next image we can see the PCB with the Ground Plane, this helps for noise filter on the pcb.

Here after we finish the pcb layout We can get the Gerber files, there are two kind of gerber files we have to pay attention to it, the first GerberX2 and the other Gerber RS274X, most of the manufacturer use the second one Gerber RS274X, in some software we will just GerberX2 and Gerber (In the case of Altium Designer).

# 3D VIEW
One of the features of Altium Designer is the 3D visualization, the 3d visualization is important and it give us the posibility to see and check our PCB and how it would be in real, also it can show us the components distribution and dimensions.

# How to Order on JLCPCB
You have to create and user account, it is free and will keep all your order historial

1.Upload the Gerber fileshttps://jlcpcb.com/IAT
2.Indicate the Features
3.Add your shipping address
4.Make the payment and finish the order
5.Receive your PCB

# Why JCLPCB?
JLCPCB has been at the forefront of the PCB industry. With over 14-year continuous innovation and improvement based on customers' need, we have been growing fast, and becoming a leading global PCB manufacturer, who provides the rapid production of high-reliability and cost-effective PCBs and creates the best customer experience in the industry.

Most Efficient, Economic, Innovative PCB Solutions
Higher Quality
Lower Cost
Faster Delivery

# Building the PCB
Attached you will find the BOM (bill of materials) needed to build the PCB, as you can see in the list you can the designator that You can check also with the schematic circuit.
