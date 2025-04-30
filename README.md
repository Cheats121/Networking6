# Networking6
EIGRP + OSCP
-------------------
# Lab 6: OSPF & EIGRP

### Overview
Swapped RIP for OSPF in Part 1 and EIGRP in Part 2 to compare IGP behaviours.

### Topology
- Same as Lab 5: multiple /29 subnets and 4 routers.

### Tasks & Results
1. **OSPF Configuration**  
   - `router ospf 10`; advertised networks; observed FULL/DR/BDR states.

2. **Failure & Convergence**  
   - Shutdown R1’s interface; captured LS Update and reconvergence.

3. **EIGRP Configuration**  
   - `router eigrp 100`; advertised networks; monitored neighbor SRTT & RTO.

### Lessons Learned
- OSPF’s area concept, DR/BDR roles, LSDB updates.
- EIGRP’s diffusion updates and fast convergence metrics.
