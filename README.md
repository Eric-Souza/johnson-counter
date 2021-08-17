# Johnson Counter

The Johnson Ring Counter consists of a number of counters connected together with the output fed back to the input. This implementation's expected output is:

0 clk=0, out= xxxx, reset=1
5 clk=1, out= 0000, reset=1
10 clk=0, out= 0000, reset=1
15 clk=1, out= 0000, reset=1
20 clk=0, out= 0000, reset=0
25 clk=1, out= 0001, reset=0
30 clk=0, out= 0001, reset=0
35 clk=1, out= 0011, reset=0
40 clk=0, out= 0011, reset=0
45 clk=1, out= 0111, reset=0
50 clk=0, out= 0111, reset=0
55 clk=1, out= 1111, reset=0
60 clk=0, out= 1111, reset=0
65 clk=1, out= 1110, reset=0
70 clk=0, out= 1110, reset=0
75 clk=1, out= 1100, reset=0
80 clk=0, out= 1100, reset=0
85 clk=1, out= 1000, reset=0
90 clk=0, out= 1000, reset=0
95 clk=1, out= 0000, reset=0
100 clk=0, out= 0000, reset=0
