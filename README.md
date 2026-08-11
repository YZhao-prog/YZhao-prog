<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:BE2EDD,100:20B2AA&height=120&section=header&text=Yang%20Zhao&fontSize=38&fontAlignY=35"/>

<h3>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1200&color=20B2AA&center=true&vCenter=true&width=600
&lines=Backend+%2F+Distributed+Systems+Engineer;
ex-Software+Engineer+Intern+%40+Splunk;
Storage+%7C+Consistency+%7C+Reliability" />
</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/yang-zhao-48b12431a/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" height="30"/>
  </a>
  &nbsp;
  <a href="mailto:yangzhao200124@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" height="30"/>
  </a>
  &nbsp;
  <a href="https://github.com/YZhao-prog">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" height="30"/>
  </a>
</p>

</div>

---

## About Me

Backend-focused engineer with hands-on experience in **production distributed systems**.

- Former **Software Engineer Intern at Splunk**, working on storage pipelines and cross-node consistency in large-scale search clusters.
- Interested in **distributed systems, databases, and reliability engineering**.
- Enjoy working close to **storage engines, consistency protocols, and system performance**.

---

## Technical Focus

- Distributed consensus & replication (**Raft**)
- Consistency & concurrency control (**Linearizability**, **MVCC**)
- Storage systems (**LSM-tree**, compaction, caching)
- Backend reliability and fault tolerance

---

## 🧠 Engineering Philosophy

Some opinions I tend to stick to:

- ✅ **Correct before fast** (performance comes after invariants)
- 🔍 Make **failure modes explicit**
- 🛠 Design for **operability, not just happy paths**
- 📈 Benchmark before assuming something is “fast enough”

I enjoy reading systems papers, implementing ideas from scratch, and validating designs through experiments and benchmarks — then questioning my own assumptions.

---

## 🚀 Featured Projects

### [SharkDB](https://github.com/YZhao-prog/SharkDB) — SQL database engine from scratch in Rust

Hand-written parser → rule-based optimizer → parallel executor, over MVCC snapshot-isolation transactions and **three interchangeable storage engines** (in-memory B-tree, Bitcask-style log, LSM-tree) behind one trait.

- **LSM-tree engine**: WAL + memtables, block-based SSTables with Bloom filters, leveled compaction — crash recovery **~16× faster** than full-log replay
- **Optimizer**: constant folding, predicate pushdown, PK point-lookup rewriting (full scan → O(1) read), hash-join selection, `EXPLAIN`
- **Parallel execution**: scoped-thread scan/filter/two-phase aggregation — **~2× end-to-end** on 200K-row analytical queries
- Diagnosed & fixed a classic **LSM tombstone anti-pattern** in the MVCC layer: point lookups 163 → 20.7K QPS (**127×**)

### [raft-kv](https://github.com/YZhao-prog/raft-kv) — fault-tolerant sharded KV store in Go

Raft consensus (leader election, log replication, persistence, snapshot compaction) under network partitions; linearizable KV service with request dedup and at-most-once semantics; dynamic shard migration and rebalancing across Raft-backed replica groups.

---

## 📊 GitHub Overview

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=YZhao-prog&theme=github"/>
</div>

---

## 🐍 Contribution Activity

<p align="center">
  <img src="https://github.com/YZhao-prog/YZhao-prog/blob/output/github-contribution-grid-snake.svg" alt="contribution snake"/>
</p>
