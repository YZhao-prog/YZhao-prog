<div align="center">

# 👋 Hi, I’m Yang Zhao  
### ex-Software Engineer Intern @ Splunk | MS in Information Systems @ Northeastern  

![](https://img.shields.io/badge/Focus-Distributed_Systems_and_Databases-BE2EDD)
![](https://img.shields.io/badge/Focus-Backend_and_System_Programming-BE2EDD)
![](https://img.shields.io/badge/Role-Software_Engineer-20B2AA)

<p>
  <a href="https://www.linkedin.com/in/yang-zhao-48b12431a/">
    <img src="https://img.shields.io/badge/LinkedIn-ffffff?style=for-the-badge&logo=linkedin&logoColor=black"/>
  </a>
  <a href="mailto:zhao.yang11@northeastern.edu">
    <img src="https://img.shields.io/badge/Email-ffffff?style=for-the-badge&logo=gmail&logoColor=black"/>
  </a>
  <a href="https://github.com/YZhao-prog">
    <img src="https://img.shields.io/badge/GitHub-ffffff?style=for-the-badge&logo=github&logoColor=black"/>
  </a>
</p>

</div>

---

## 🧭 About Me

- Backend-focused engineer interested in **distributed systems, databases, and performance-critical software**.
- **Former Software Engineer Intern at Splunk**, working on reliability and scalability of large-scale distributed platforms.
- Currently pursuing a **Master’s in Information Systems at Northeastern University**.

---

## 🛠 Tech Stack

**Languages:** C, C++, Rust, Java, Python, JavaScript, SQL  
**Backend & Systems:** gRPC, REST, Spring Boot, Node.js, Linux  
**Databases:** MySQL, PostgreSQL, MongoDB, Redis, RocksDB  
**Distributed Systems:** MVCC, LSM-tree, Snapshot Isolation, Raft  
**DevOps:** Git, Docker, Kubernetes

---

## 🚀 Projects

### **Distributed SQL Database**  
*Rust · SQL · Redis · RocksDB · MVCC · LSM-tree*

A distributed SQL database built from scratch, focusing on query processing, storage engines,
and transactional consistency.

- Engineered a SQL parser and lexer using `nom` parser combinators, supporting complex nested queries
  with robust error recovery.
- Implemented a cost-based query optimizer with dynamic statistics collection, enabling join
  reordering and predicate pushdown.
- Developed a parallel execution engine to improve throughput for analytical workloads.
- Built a hybrid storage layer using RocksDB for persistence and Redis for caching.
- Implemented a custom LSM-tree with compaction strategies and Bloom filters for efficient range scans.
- Designed an MVCC system with snapshot isolation and optimistic concurrency control.
- Implemented a gRPC-based replication protocol using the Raft consensus algorithm.

---

### **RISC-V Operating System Kernel**  
*C · C++ · RISC-V · Assembly*

An educational operating system kernel implementing core OS subsystems on RISC-V.

- Developed a virtual memory subsystem with multi-level page tables and TLB support.
- Implemented copy-on-write and lazy allocation to reduce memory usage and improve `fork()` performance.
- Designed a priority-based O(1) scheduler with custom coroutine context switching.
- Reduced lock contention using fine-grained read-write locks under multi-process workloads.
- Enhanced the file system with extents and indirect blocks to support large files.
- Implemented zero-copy `mmap`, symbolic links, and optimized file I/O paths.
- Built precise interrupt handling with nested interrupt support and timer-based system calls.

---

### **High-Performance Database Engine**  
*C++ · SQL · MVCC*

A single-node database engine focusing on concurrency control, indexing, and query execution.

- Engineered a concurrent buffer pool with scalable hash tables and LRU-K eviction.
- Implemented B+ tree indexes with fine-grained read-write locks for concurrent access.
- Built a vectorized query execution engine supporting joins and aggregations.
- Designed a distributed lock manager with deadlock detection.
- Implemented MVCC with multiple isolation levels and hierarchical intention locks.
