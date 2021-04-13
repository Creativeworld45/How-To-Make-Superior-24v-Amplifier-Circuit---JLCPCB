# How-To-Make-Superior-24v-Amplifier-Circuit---JLCPCB

Thanks To JLCPCB.

$2 For 1-4 Layer PCBs.

Get SMT Coupons : https://jlcpcb.com/RTA

------------------------------------------------------

In this project, we’ll teach you making a simple superior 24v amplifier circuit. To make this circuit we are using transistor. If you have DC-24v adapter or 24v battery, then you also can make this amplifier circuit at home easily. 
To make this circuit we might need some electronics component. Those component list have to been given below.

Component List : 
1. Transistor –  D 1047
                 BC 547
                 B 817                         
2. Resistor – 1 KΩ
              100 KΩ
              2.2 Ω *2
3. Diode – 1N5399 *2
4. Capacitor - 1000µf/25v
               2.2µf/50v
5. Audio Input Cable
6. Sound Speaker
7. Power Source – DC 24v
8. Heat Sink
9. Soldering Iron
10. 

Transistor Pinout : 
To make this 24v amplifier circuit, we are using 3 transistor. We everybody know that, all transistor and mosfet have 3 legs. But this 3 legs have different names. 1st we know the pinout of these 3 transistors.

Transistor Number ----------Type ----------- Pinout

        D-1047   ------------ NPN-----------1no Base, 2no Collector, 3no Emitter
        
        B-817---------------  PNP-----------1no  Base, 2no Collector, 3no Emitter
        
        BC-547----------------NPN-----------1no  Collector, 2no Base, 3no Emitter
        

Circuit Connection :

1st we fix transistor with heat sink. We’ll fix D-1047 Transistor at left side and B-817 Transistor at right side. But we have to remember that, while we connect transistor with heat sink, then we might need to use separator.

Now, we connect 1 kΩ resistor with Base & collector of D-1047 transistor. Then we connect diode positive leg with Base of D-1047 transistor & other diode negative leg with Base of B-817 transistor. Now we connect both diode negative & positive leg. 

Now, we connect BC-547 transistor with the circuit. Connect BC-547 transistor collector with base of B-817 transistor & BC-547 transistor emitter with collector of B-817 transistor.

Now, we connect 2.2Ω resistor with the circuit. Connect resistor with emitter of D-1047 transistor and other resistor with emitter of B-817 transistor. And connect both resistor empty terminal. 

Now, we connect 100 kΩ resistor with the circuit. Connect this resistor with Base of BC-547 transistor and the place, where the both 2.2Ω resistor empty terminal is connected.

Now, we connect 1000µf/25v capacitor with the circuit. Connect capacitor positive leg with the place, where the both 2.2Ω resistor empty terminal is connected.
Now, connect 2.25µf/50v capacitor with the circuit. Connect capacitor negative leg with base of BC-547 transistor. 

Now, we connect audio input cable with the circuit. Connect audio input “L/R” cable with 2.25µf/50v capacitor positive leg and audio input “G” cable with collector of B-817 transistor.

It is the time to connect speaker cable and power cable with the circuit. 1st we connect speaker cable with the circuit. Connect speaker cable with 1000µf/25v capacitor negative leg and other speaker cable with collector of B-817 transistor.
For power source we are using DC-24v. Connect DC-24v Positive cable with collector of D-1047 transistor and negative cable with collector of B-817 transistor.

Our circuit is completely ready for use now. Now just plug-in DC 24v and collect audio input cable with mobile or audio source & ENJOY the MUSIC.
