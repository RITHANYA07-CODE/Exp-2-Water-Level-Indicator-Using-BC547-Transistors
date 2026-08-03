# Exp-2-Water-Level-Indicator-Using-BC547-Transistors

**Aim**

To design and implement a Water Level Indicator using BC547 transistors, LEDs, and a buzzer to monitor different water levels in a tank and provide visual and audible indications when the tank is full.

**Apparatus Required**

<img width="627" height="602" alt="image" src="https://github.com/user-attachments/assets/6b4bd9d0-d0ba-4935-8de6-84b5a51dea0b" />

**Circuit Diagram**

<img width="709" height="715" alt="image" src="https://github.com/user-attachments/assets/23c77019-51ee-4e12-9c44-bf9815cad42b" />

**Theory**

A Water Level Indicator is an electronic circuit used to detect the level of water in a storage tank. It helps prevent water overflow and ensures efficient water management.

The circuit operates on the principle of electrical conductivity of water. Water containing dissolved minerals conducts a small amount of electricity. Metal probes are placed at different levels inside the tank.

When the water reaches a particular probe:

A small current flows through the water.

The corresponding BC547 NPN transistor receives base current.

The transistor switches ON.

The corresponding LED glows, indicating the water level.

In this circuit:

Point A (Low Level): Red LED glows.

Point B (Medium Level): Yellow LED glows.

Point C (High Level): White LED glows.

Tank Full: White LED remains ON and the buzzer sounds, indicating that the tank is full.

The resistors limit the current through the LEDs and transistor bases, protecting the components from excessive current.

**Procedure**

1.Assemble the circuit as shown in the circuit diagram.

2.Connect the 9V battery to power the circuit.

3.Insert four metal probes into the water tank:

4.One common probe at the bottom.

5.Three sensing probes at different heights (A, B, and C).

6.Initially, keep the tank empty and observe that all LEDs remain OFF.

7.Slowly pour water into the tank.

8.Observe the indications:

9.When water reaches Point A, the Red LED turns ON.

10.When water reaches Point B, the Yellow LED also turns ON.

11.When water reaches Point C, the White LED turns ON.

12.At the full water level, the buzzer sounds, indicating the tank is full.

13.Remove the water gradually and observe that the LEDs turn OFF in reverse order.

14.Record the observations.

**Observation Table:**

<img width="562" height="328" alt="image" src="https://github.com/user-attachments/assets/94e7f551-a79b-46d1-94b8-63372348dc15" />

**Output:**

<img width="1333" height="368" alt="image" src="https://github.com/user-attachments/assets/8364a7de-26e0-4a97-a352-e006ea0acc9d" />

**Result:**

The Water Level Indicator was successfully implemented using BC547 transistors. The circuit accurately indicated the water level through LEDs and generated an audible alarm using the buzzer when the water reached the maximum level.
