# DPDK_PacketBlaster
Multi socket aware stateless packet generator using IA DPDK utility. 

Main Features:-
1) Identifies the Physical Cores, Logcial cores, Ports
2) Optimally run worker threads for stateless packet generation. 
3) Configured and Managed via INI during startup and run time.
4) Support for 1G & 10G multi socket NIC interfaces.
5) Simplistic GUI by managment core (socket 0 master core).
