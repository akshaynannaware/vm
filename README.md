Virtual Memory Manager(VMM)
==

Virtual memory manager written in C, using a backing store, physical memory, page table, and a translation lookaside buffer (TLB).
Usage: ./a.out addresses.txt




VMM is an interface between software and physical/virtual memory.

VMM provides a set of memory addresses to each program.

Memory is allocated in 4KB segments (pages).

Pages are stored in RAM or swap file on the hard drive.

Some guidelines for managing memory:

    If drive space is limited, limit maximum size of page file.

    If RAM space is limited, expand page file size to 4 GB.

    Spread page file over several physical devices.

    Do not completely eliminate virtual memory!
