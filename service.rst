Service Levels
==============

Level 0
-------

Verification of fibers state prior to the startup process.

:Summit: 1 FTE
:Base: 0 FTE
:Time: 3 hours
         
========================= ======== ==============
Activity                  Location IPAM Link
========================= ======== ==============
Visual inspection         N/A      N/A
Fiber checks              N/A      N/A
========================= ======== ==============
         
Level 1
-------

Minimal connection at the summit with link to the base. Wired and Wireless are available.

Requires verification of the AURA DWDM at Casete Pachion with NOIRLab 

:Summit: 2 FTE 
:Base: 1 FTE
:Time: 6 hours


========================= ======== ==============
Device                    Location IPAM Link
========================= ======== ==============
Core Switches             Rack ?   link
Distribution Switches     Rack ?   link
Wireless Lan Controller   Rack ?   link
Access Switches           Rack ?   link
DWDM                      Rack ?   link
Core Cluster              Rack ?   link
DNS                       Rack ?   link
DHCP                      Rack ?   link
========================= ======== ==============

Level 2
-------

Level 1 + Telephony and Video Conference. 

Requires reset of all IP phones.

:Summit: 1 FTE
:Base: 0 FTE
:Time: 3 hours

========================= ========== ==============
Device                    Location   IPAM Link
========================= ========== ==============
Cisco BE6K                Rack       link
Video Conference          Conf. Room -
========================= ========== =============

Level 3
-------

Level 2 + Monitoring

:Summit: 1 FTE
:Base: 0 FTE
:Time: 6 hours

========================= ======== ==============
Device                    Location IPAM Link
========================= ======== ==============
APIC 1                    Rack ?   link
Leaf 01 and 03            Rack ?   link
APIC 2 and 3              Rack ?   link
Border Leafs              Rack ?   link
Remaining Leafs           Rack ?   link
HVAC Server               Rack ?   link
========================= ======== ==============

