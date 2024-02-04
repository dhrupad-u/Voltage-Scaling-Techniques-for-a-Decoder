# Voltage-Scaling-Techniques-for-a-Low-Power-Decoder

There are many different methods which are implemented in a modern IC Design to minimize power usage 
and extend the life cycle of an integrated circuit. One of the most widely used techniques called as 
voltage scaling, under which once again are many derivatives that have been in use for quite a while 
in the industry. This project aims to explore a couple of those voltage scaling techniques, with the 
objective of reducing power consumption while maintaining the same performance. The main techniques 
used here are:

1. Reduced Voltage technique
2. Body Biasing
   
A decoder(s) is designed using the HSPICE software, to simulate and analyze the effect of various scaling 
techniques, to finalize on which methodology yields the most ideal results.

The project discussed in this report contains three different decoder designs:

1. 2 to 4 Decoder
2. 3 to 8 Decoder
3. 4 to 16 Decoder
   
Each of these designs are subject to the analysis where they are first simulated without applying any scaling 
techniques and the second one is to make changes in-terms of voltage scaling

1. 2 to 4 Decoder

   ![image](https://github.com/dhrupad-u/Voltage-Scaling-Techniques-for-a-Decoder/assets/42469685/3260061b-80e9-40c8-b66b-03556da2263c)

3. 3 to 8 Decoder

   ![image](https://github.com/dhrupad-u/Voltage-Scaling-Techniques-for-a-Decoder/assets/42469685/3816e6fe-d5f2-4522-acef-1c5ba1437b42)

5. 4 to 16 Decoder

   ![image](https://github.com/dhrupad-u/Voltage-Scaling-Techniques-for-a-Decoder/assets/42469685/fb162cfb-d575-424a-b319-a035b6f2bc6a)

Each Decoder design contains two folders:

1. Static Power Analysis
2. Dynamic Power Analysis

The .sp file contains the HSPICE code and the rest of the files in these folers are the results obtained after the simulation.

The .mt0 file can be used to check the results of the power dissipated from these individual simulations.

  
