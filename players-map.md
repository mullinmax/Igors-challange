```mermaid
graph TB;




r1[Entry]
r2
r3[Mirror maze]
r4

r1-->r2
r1-->r3
r1-->r4
r3-->|right|r5
r5[chess & dominos]
r7[fake wall]
r3-->|left|r6
r5-->|right|r7
r5-->|left|r8
r7-->|left|r9
r7-->|right|r10
r10-->r11
r10[YMCA]
r9-->r12

key1[visited]
key2[you are here]
key3[locked]

classDef visited fill:#4D2;
class key1,r1,r3,r5,r7,r9,10 visited;

classDef here fill:#22F;
class key2,r9 here;

classDef locked fill:#F0F;
class key3,r8,r6,r11,r12 locked;
