# DPDK_PacketBlaster
Multi socket aware stateless packet generator using IA DPDK utility. 

Features:-
1) Identifies the Physical Cores, Logcial cores, Ports.
2) Optimally run worker threads for stateless packet generation. 
3) Configured and Managed via INI during startup and run time.
4) Support for 1G & 10G multi socket NIC interfaces.
5) Simplistic GUI by managment core (socket 0 master core).

Build:-
export RTE_SDK=<<DPDK PATH to SDK>>
export RTE_TARGET=x86_64-native-linuxapp-gcc

Add & Mount Huge page.

make clean; make; ./build/PktBlaster  -c <<core mask>> -n <<memory controller count>>

[[stats.png]]
