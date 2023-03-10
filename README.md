TECTONIC: TOWARDS EMPLOYING COMPILERS FOR THERMAL MANAGEMENT AND OPTIMAL DATA PLACEMENT IN HYBRID CACHE
-------------------------------------------------------------------------------------------------------

Project Details:
--------------------
Source of funding: Marie Curie Individual Fellowship Individual Fellowship (MSCA-IF) 

Amount: EUR 214,158.72 (from EU)

Project ID: 898296

Host Institute: Norwegain University of Science and Technology (NTNU), Trondheim, Norway

Brief Technical Description:
----------------------------
  Stagnation in process technology drove architects and researchers towards investigating new emerging non-volatile memory (NVM) technologies for designing on-chip last level caches (LLCs). The promise of better scalability with reduced static leakage makes NVMs potential candidates for replacing conventional
SRAM. However, many of the NVMs have reduced durability compared to SRAM and the durability is often further reduced at increased temperature. Some of these NVMs (e.g., spin transfer torque RAM (STTRAM)) are promising alternatives due to their fast response time, small cell-size, and high compatibility with CMOS processes. However, SRAM still has better writing speed and write endurance, hence, making a hybrid SRAM/NVM based LLC will potentially be a better solution than any single memory technology design. To achieve the best of both, hybrid SRAM/NVM based LLC, which we adopt in this work, has become a topic of paramount importance, over the recent years. TECTONIC will alleviate both (i) the challenging problem of generated hotspots at the CPU-registers in 3D chip multi-processors (3D-CMPs), and (ii) the lower write endurance of STTRAM, by incorporating optimal workload distribution at the respective levels of the memory hierarchy. In particular, TECTONIC will manage the on-chip temperature by leveraging application specific knowledge extracted at compile time in combination with new hardware mechanisms to distribute cache accesses to mitigate thermal imbalance and to reduce write endurance while maintaining high performance. Specifically, TECTONIC will meet the following objectives: 
  1. To establish a relationship between data accesses and hot-spots at the CPU registers by investigating compute-intensive loops of contemporary large-scale applications (e.g., multi-media based applications, heavy algebraic computation etc.). 
  2. To employ loop splitting towards ameliorating the write endurance problem in NVMs. 
  3. To investigate the benefits of dynamic swapping of the contents of cache ways based upon write intensity. 
  4. The knowledge deduced by the above investigations will enable us to analyse PowerPerformance-Thermal trade-offs and develop an optimal thermal-aware data placement strategy for NVM-based hybrid cache.
  
  Additionally, the unavailability of proper architectural thermal simulators that can simulate the thermal
behaviours of NVM-based hybrid caches keep this research area unexplored. Hence, the implementation of
TECTONIC includes the creation of such a simulation framework, which will not only help us to accomplish
the goals of TECTONIC, but will also kick off new research avenues.

Publications:
-------------
Publications related to this projects can directly be downloaded from here, however, the final contents of the paper might be different. The simulation data and the fundamental concepts of the paper are same. 

