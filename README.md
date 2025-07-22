# Four-Bit-Synchronous-MOD-N-counter-with-Asynchronous-reset

**OBJECTIVE**

Write a verilog code for 4-bit Synchronous MOD-N counter with Asynchrounous reset,
verify the functionality using Test bench and Synthesize the design and compare the synthesis
report.

**DESCRIPTION**

Counters are sequential logic devices that follow a predetermined sequence of counting states
triggered by an external clock (CLK) signal. The number of states or counting sequences through
which a particular counter advances before returning to its original first state is called the modulus
(MOD). In other words, the modulus (or modulo) is the number of states the counter counts and is
the dividing number of the counter.

Modulus Counters, or MOD counters, are defined based on the number of states that the counter
will sequence before returning to its original value.

For example, a 2-bit counter that counts from 002 to 112 in binary, 0 to 3 in decimal, has a
modulus value of 4 ( 00 → 1 → 10 → 11, and return to 00 ); therefore, be called a modulo-4, or
mod-4, counter. Note also that it has taken four clock pulses to get from 00 to 11.
In this example, there are only two bits ( n = 2 ) then the maximum number of possible output
states (maximum modulus) for the counter is 2n = 22 or 4. However, counters can be designed to
count to any 2n states in their sequence by cascading together multiple counting stages to produce
a single modulus or MOD-N counter.

Therefore, a "Mod-N" counter will require the "N" number of flip-flops connected to count a single
data bit while providing 2n different output states (n is the number of bits). Note that N is always
a whole integer value. Then we can see that MOD counters have a modulus value that is an integral
power of 2, that is, 2, 4, 8, 16 and so on to produce an n-bit counter depending on the number of
flip-flops used, and how they are connected, determining the type and modulus of the counter.

**OUTPUT SIMULATION**


<img width="785" height="118" alt="Image" src="https://github.com/user-attachments/assets/a878f84b-68f0-40f6-81a9-66b47b6ddbd2" />


**OUTPUT SYNTHESIS**



<img width="934" height="209" alt="Image" src="https://github.com/user-attachments/assets/09540330-73d9-4aa8-a8b3-d0e31f8845d9" />
