# Cisco_TextFSM
Template collects data about power consumption from cisco devices. Output data may be couse of problem. I suggest to
use divided templates ( for modules and separatly for interfaces )

SAMPLE DATA
Module   Available     Used     Remaining
          (Watts)     (Watts)    (Watts)
------   ---------   --------   ---------
1           370.0      212.0       158.0
2           370.0      117.0       253.0
Interface Admin  Oper       Power   Device              Class Max
                            (Watts)
--------- ------ ---------- ------- ------------------- ----- ----
Gi1/0/1   auto   on         15.4    MikroTik            4     30.0
Gi1/0/2   auto   on         13.8    WirelessAP          4     30.0
Gi1/0/3   auto   on         13.0    GXP2170             0     30.0
Gi1/0/4   auto   off        0.0     n/a                 n/a   30.0
Gi1/0/5   auto   off        0.0     n/a                 n/a   30.0
...
