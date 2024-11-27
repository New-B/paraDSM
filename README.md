# paraDSM
This ia a distributed parallel programming model running on a DSM(Distributed Shared Memory) system.

The parallel programming model follows the fork-join pattern, enabling parallelism not only within nodes but also among nodes.

This DSM system connects the memory resources of multiple nodes into a single logically unified address space through RDMA. The exposed APIs allow for allocation, free, read, and write on the DSM, while ensuring consistency for all memory operations.
