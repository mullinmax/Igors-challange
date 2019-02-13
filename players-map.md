```mermaid
graph TB;
classDef hidden display:none,stroke:0px;
classDef locked fill:#77F;
classDef visited fill:#4D2;
classDef here fill:#D22;

subgraph key
key1[visited]
class key1 visited;
key2[you are here]
class key2 here;
key3[locked]
class key3 locked;
end

r1[Entry]
r2
r3[Mirror maze]
click r3 "https://github.com/mullinmax/Igors-challange/blob/master/igor-rooms.md#room-3"
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
class key1,r1,r3,r5,r7,r9,10 visited;
class key3,r8,r6,r11 locked;

r9[disco dance];
class r9 here;
click r9 "https://github.com/mullinmax/Igors-challange/blob/master/igor-rooms.md#room-5"

r9-->r12%%[four bowls]
%%class r12 visited;
%%class r12 here;
class r12 locked;
click r12 "https://github.com/mullinmax/Igors-challange/blob/master/igor-rooms.md#room-12"

r6_5%%[pick your path]
%%class r6_5 visited;
%%class r6_5 here;
class r6_5 hidden;
%%r6_5-->t
%%r6_5-->t
%%r6_5-->t
%%r6_5-->t
%%r6_5-->t
%%r6_5-->t
%%r6_5-->t
%%r6_5-->t
%%r6_5-->t
%%r6_5-->t
%%r6_5-->r6_6
click r6_5 "https://github.com/mullinmax/Igors-challange/blob/master/igor-rooms.md#room-6_5"

6_5%%[seated stairs]
%%class r6_6 visited;
%%class r6_6 here;
%%class r6_6 locked;
class r6_6 hidden;
click r6_6 "https://github.com/mullinmax/Igors-challange/blob/master/igor-rooms.md#room-6_6"
```


rn
%%class rn visited;
%%class rn here;
%%class rn locked;
class rn hidden;
click rn "https://github.com/mullinmax/Igors-challange/blob/master/igor-rooms.md#room-7"