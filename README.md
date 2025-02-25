<div align="center">
  
# 🌟 Hello World, I'm Yang Zhao  
### Master's Student in Information Systems | Software Engineer  

![](https://img.shields.io/badge/Focus-Scalable_Systems_and_Databases-BE2EDD)
![](https://img.shields.io/badge/Focus-Full_Stack_Development-BE2EDD)  
![](https://img.shields.io/badge/Role-Software_Developer-20B2AA)

<p>
  <a href="https://www.linkedin.com/in/yang-zhao-48b12431a/"><img src="https://img.shields.io/badge/LinkedIn-ffffff?style=for-the-badge&logo=linkedin&logoColor=black"/></a>
  <a href="mailto:zhao.yang11@northeastern.edu"><img src="https://img.shields.io/badge/Email-ffffff?style=for-the-badge&logo=gmail&logoColor=black"/></a>
  <a href="https://github.com/YZhao-prog"><img src="https://img.shields.io/badge/GitHub-ffffff?style=for-the-badge&logo=github&logoColor=black"/></a>
</p>

</div>

## 🎯 About Me  

- 🔭 Focused on building scalable systems and optimizing databases.  
- 🌱 Passionate about full-stack web development and system programming.  
- 🎓 Currently pursuing a Master's in Information Systems at Northeastern University.  

## 💻 Tech Stack  

### 🖥️ Programming Languages  
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)  

### 🎨 Web Development  
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)  

### 🗄️ Databases  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white) ![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)  

### 🛠️ Development Tools  
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![NPM](https://img.shields.io/badge/NPM-CB3837?style=for-the-badge&logo=npm&logoColor=white) ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)  

### 📈 Testing & Performance Analysis  
![Unit Testing](https://img.shields.io/badge/Unit_Testing-6DB33F?style=for-the-badge&logo=pytest&logoColor=white) ![Performance Analysis](https://img.shields.io/badge/Performance_Analysis-00897B?style=for-the-badge)    

## 🚀 Projects  

### [Distributed SQL Database](https://github.com/YZhao-prog/SharkDB) | Rust, SQL, Redis, RocksDB | Sep 2024 – Present  
- **Query Engine**: Engineered a high-performance SQL parser and lexer achieving 99.9% query parsing accuracy, with intelligent error recovery and support for complex nested queries, utilizing `nom` parser combinators for robust AST generation.  
- **Query Optimization**: Implemented a cost-based optimizer with dynamic statistics collection, reducing query execution time by 40% through intelligent join ordering and predicate pushdown, integrated with parallel execution for 3x throughput improvement.  
- **Storage Layer**: Developed a hybrid storage engine combining RocksDB for persistence and Redis for caching, with custom LSM-tree implementation achieving 50,000 QPS for point queries and 10,000 QPS for range scans.  
- **Transaction Management**: Built an MVCC system supporting snapshot isolation with optimistic concurrency control, achieving a 95% success rate for concurrent transactions and sub-millisecond commit latency for 90th percentile operations.  

### Operating System Kernel Based on RISC-V ISA | C, C++, RISC-V, Assembly | May 2024 – Jul 2024  
- **Memory Subsystem**: Engineered a sophisticated virtual memory system with 4-level page tables and TLB, implementing zero-copy copy-on-write and lazy allocation reducing memory usage by 30% and improving `fork()` performance by 2x.  
- **Process Scheduler**: Developed a priority-based scheduler with O(1) task switching, implementing user-space coroutines with custom context switching achieving 100,000 switches/second, and fine-grained RW-locks reducing contention by 45%.  
- **File System**: Enhanced the file system with extents and indirect blocks, increasing maximum file size from 268KB to 65803KB, while implementing zero-copy `mmap` and symbolic links reducing I/O overhead by 25%.  
- **Interrupt Handling**: Implemented precise interrupt handling with nested interrupt support, adding new system calls with 99.9% reliability and microsecond-level timer resolution for the alarm subsystem.  

### High-Performance Database Engine | C++, SQL, MVCC | Sep 2023 - Dec 2023  
- **Buffer Management**: Engineered a concurrent buffer pool with scalable hash tables and LRU-K eviction, achieving 95% hit rate and supporting 10,000 concurrent connections with sub-millisecond page access latency.  
- **Index Layer**: Implemented lock-free B+ trees with RCU synchronization, supporting 100,000 QPS for point queries and maintaining ACID properties with node-level read-write locks, reducing contention by 60%.  
- **Query Processing**: Built a vectorized query executor supporting complex operations (`SELECT`, `INSERT`, `GROUP BY`, `JOIN`) with Volcano model, achieving 50,000 rows/second throughput for analytical queries.  
- **Transaction Control**: Designed a distributed lock manager with deadlock detection, supporting MVCC with three isolation levels (RR, RC, RU) and hierarchical intention locks, maintaining 99.9% transaction completion rate under high concurrency.   

## 📈 GitHub Stats  

  <img align="center" height="180em" src="https://github-readme-stats.vercel.app/api?username=YZhao-prog&show_icons=true&theme=radical&count_private=true" alt="YZhao's GitHub Stats" />
  
  <img align="center" height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YZhao-prog&layout=compact&langs_count=8&theme=radical&hide=html,css" alt="Top Languages" />

## 📈 Contribution Timeline  

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=YZhao-prog&theme=dracula" alt="Contribution Timeline"/>
</div>
