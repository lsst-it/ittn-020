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
Visual inspection         -        -
Fiber checks              -        -
========================= ======== ==============


Level 1
-------

Minimal connection at the summit with link to the base. Wired and Wireless are available.

Requires verification of the AURA DWDM at Caseta Pachon with NOIRLab

:Summit: 2 FTE
:Base: 1 FTE
:Time: 6 hours

========================= ======== =============================================
Device                    Location IPAM Link
========================= ======== =============================================
Core Switches             Rack A3  https://ls.st/vgm
Distribution Switches     Rack A3  https://ls.st/uof
Wireless Lan Controller   Rack A4  https://ipam.ls.lsst.org/dcim/devices/45/
Access Switches           Rack A3  https://ls.st/l3l
DWDM                      Rack A7  https://ipam.ls.lsst.org/dcim/devices/14/
Core Cluster              Rack A1  https://ls.st/bya
DNS                       -        https://ls.st/g9w
DHCP                      -        https://ls.st/oxg
========================= ======== =============================================


Level 2
-------

Level 1 + Monitoring and building cameras

:Summit: 1 FTE
:Base: 0 FTE
:Time: 6 hours

========================= ======== =============================================
Device                    Location IPAM Link
========================= ======== =============================================
APIC 1                    Rack A4  https://ipam.ls.lsst.org/dcim/devices/48/
Spine 1                   Rack A3  https://ipam.ls.lsst.org/dcim/devices/41/
Spine 2                   Rack A4  https://ipam.ls.lsst.org/dcim/devices/52/
Leaf 01                   Rack A1  https://ipam.ls.lsst.org/dcim/devices/29/
Leaf 03                   Rack A5  https://ipam.ls.lsst.org/dcim/devices/10/
APIC 2                    Rack A4  https://ipam.ls.lsst.org/dcim/devices/49
APIC 3                    Rack A4  https://ipam.ls.lsst.org/dcim/devices/50
Border Leaf 09            Rack A7  https://ipam.ls.lsst.org/dcim/devices/11/
Border Leaf 10            Rack A7  https://ipam.ls.lsst.org/dcim/devices/12/
Remaining Leafs           Several  https://ls.st/pq1
HVAC Server               Rack B2  https://ipam.ls.lsst.org/dcim/devices/75/
3rd Floor Switch Camera   -        -
5th Floor Switch Camera   -        -
========================= ======== =============================================


Level 3
-------

Level 2 + Main Computing

Requires 1 extra FTE from Software group to verify the software.

:Summit: 1 FTE
:Base: 1 FTE
:Time: 4 hours

========================= ======== =============================================
Device                    Location   IPAM Link
========================= ======== =============================================
Amor cluster              Rack       link
Andes cluster             Rack       link
Azar cluster              Rack       link
========================= ======== =============================================


Level 4
-------

Level 3 + calibration hill

:Summit: 2 FTE
:Base: 1 FTE
:Time: 3 hours

================================= ======== =============================================
Device                            Location   IPAM Link
================================= ======== =============================================
Weather, Dimm and All-Sky Cab.    -          -
Main Generator Cabinet            -          -
================================= ======== =============================================


Level 5
-------

Level 4 + Building

Requires reset of ip phones.

:Summit: 2 FTE
:Base: 1 FTE
:Time: 6+ hours

================================= ======== =============================================
Device                            Location   IPAM Link
================================= ======== =============================================
1st Floor (incl. GeoVictoria)     -          -
3rd Floor (incl. M2, Hex-Rot,etc) -          -
5th Floor                         -          -
Upper Levels Wifi                 -          -
================================= ======== =============================================


Level 6
-------

Level 5 + Auxtel

Requires reset of ip phones in Auxtel.

:Summit: 2 FTE
:Base: 1 FTE
:Time: 2 hours

================================= ======== =============================================
Device                            Location   IPAM Link
================================= ======== =============================================
Auxtel Rack                       -          -
================================= ======== =============================================


Level 7
-------

Level 6 + Telephony and Video Conference.

Requires reset of all IP phones.

:Summit: 1 FTE
:Base: 0 FTE
:Time: 3 hours

========================= =========== =============================================
Device                    Location    IPAM Link
========================= =========== =============================================
Cisco BE6K                Rack A4     https://ipam.ls.lsst.org/dcim/devices/44/
Video Conference          Conf. Room  -
========================= =========== =============================================


Level 8
-------

Level 7 + all the rest

:Summit: 2 FTE
:Base: 0 FTE
:Time: 4 hours

================================= ======== =============================================
Device                            Location   IPAM Link
================================= ======== =============================================
Summit Villa                      -          -
Contractors Network               -          -
Casino                            -          -
Any other                         -          -
================================= ======== =============================================
