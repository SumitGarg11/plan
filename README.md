# Elite Backend Engineer — Complete Curriculum

**Target:** Google SWE (YouTube Backend) · HFT SWE · Elite Backend Engineer
**Duration:** 12 months · **Owner:** Sumit

> **How to use this doc**
> This is your *knowledge base* — the full syllabus + the single best resource per topic.
> Track your actual progress (Confidence, Revision D1/D3/D7/D15/D30, Status, Notes links,
> problems solved) in the **Elite Engineer OS** Google Sheet. Pull a topic from here →
> add a row in the matching tracker → grind it → mark revision dates.
>
> **Priority key:** P0 = must-know (asked constantly) · P1 = important · P2 = deepens you · P3 = niche/advanced
> **Difficulty:** ★ easy · ★★ medium · ★★★ hard · ★★★★ expert

---

## 📚 Core Resources (bookmark these once)

| Area | Single best resource | Type |
|---|---|---|
| CP theory | **cp-algorithms.com** | Free site |
| CP handbook | **Competitive Programmer's Handbook** — Antti Laaksonen (free PDF) | Book |
| CP practice | **codeforces.com** + **cses.fi/problemset** | Practice |
| CP structured | **Codeforces EDU** (edu section — Interactive, constructive, DS) | Course |
| C++ reference | **cppreference.com** | Docs |
| Modern C++ | **Effective Modern C++** — Scott Meyers | Book |
| OS | **OSTEP** (ostep.org, free) | Book |
| Networking | **Computer Networking: A Top-Down Approach** — Kurose & Ross | Book |
| Databases | **CMU 15-445** (youtube + notes) | Course |
| Distributed systems | **Designing Data-Intensive Applications** — Martin Kleppmann | Book |
| System design | **System Design Interview Vol 1 & 2** — Alex Xu | Book |
| System design (free) | **github.com/donnemartin/system-design-primer** | Repo |
| LLD / patterns | **Refactoring Guru** (refactoring.guru) | Site |
| Reliability / SRE | **Google SRE Book** (sre.google/books — free online) | Book |
| Backend patterns | **microservices.io** (Chris Richardson) | Site |
| AWS reliability | **Amazon Builders' Library** (retries, backoff) | Site |

---

# PART 1 — COMPETITIVE PROGRAMMING
*Goal: Codeforces Specialist → Expert (target 1600+). Grind daily.*

## 1.1 Foundations

| Topic | Subtopic | Diff | Pri | Best Resource | Practice |
|---|---|---|---|---|---|
| Complexity | Big-O, amortized, space | ★ | P0 | CP Handbook Ch.2 | — |
| I/O speed | Fast I/O in C++ | ★ | P0 | cp-algorithms | CF |
| STL basics | vector, map, set, pair | ★ | P0 | cppreference | CSES Intro |
| Sorting | comparator, stable sort | ★ | P0 | cp-algorithms | CF |
| Sort algorithms | merge, quick, counting, radix, heap sort | ★★ | P0 | CP Handbook Ch.3 | CSES |

## 1.2 Mathematics & Number Theory

| Topic | Subtopic | Diff | Pri | Best Resource | Practice |
|---|---|---|---|---|---|
| Number theory | GCD, LCM, Euclid | ★ | P0 | cp-algorithms | CSES Math |
| Modular arithmetic | mod inverse, Fermat | ★★ | P0 | cp-algorithms | CF |
| Sieve | Eratosthenes, linear sieve | ★★ | P0 | cp-algorithms | CSES |
| Prime factorization | smallest prime factor | ★★ | P0 | cp-algorithms | CF |
| Divisors | counting divisors, divisor sum | ★★ | P1 | cp-algorithms | CF |
| Primality test | trial division, Miller-Rabin | ★★★ | P1 | cp-algorithms | CF |
| Euler totient | φ(n), properties | ★★ | P1 | cp-algorithms | CF |
| Modular exponentiation | binary exp | ★★ | P0 | cp-algorithms | CSES |
| CRT | Chinese Remainder | ★★★ | P2 | cp-algorithms | CF |
| Matrix exponentiation | linear recurrences | ★★★ | P1 | cp-algorithms | CSES |

## 1.3 Combinatorics · Probability · Expected Value

| Topic | Subtopic | Diff | Pri | Best Resource | Practice |
|---|---|---|---|---|---|
| Combinatorics | nCr, Pascal, stars & bars | ★★ | P0 | CP Handbook Ch.22 | CF |
| Binomial mod p | precompute factorials | ★★ | P1 | cp-algorithms | CF |
| Inclusion-Exclusion | PIE | ★★★ | P1 | cp-algorithms | CF |
| Probability | basics, conditional | ★★ | P1 | CP Handbook | CF |
| Expected value | linearity of expectation | ★★★ | P1 | CP Handbook | CF |
| Derangements / Catalan | classic counts | ★★★ | P2 | cp-algorithms | CF |

## 1.4 Core Techniques

| Topic | Subtopic | Diff | Pri | Best Resource | Practice |
|---|---|---|---|---|---|
| Bit manipulation | masks, tricks, __builtin | ★★ | P0 | CP Handbook Ch.10 | CF |
| Prefix sum | 1D/2D, difference array | ★ | P0 | cp-algorithms | CSES Range |
| Two pointers | sliding window | ★★ | P0 | CP Handbook | CF |
| Binary search | on answer, monotonic | ★★ | P0 | cp-algorithms | CSES |
| Ternary search | unimodal functions | ★★ | P2 | cp-algorithms | CF |
| Greedy | exchange argument | ★★ | P0 | CP Handbook Ch.6 | CF |
| Divide & conquer | merge, D&C DP | ★★★ | P1 | cp-algorithms | CF |
| Backtracking | subsets, permutations, N-Queens, pruning | ★★★ | P0 | CP Handbook | LeetCode |
| Recursion | recurrence, base cases, recursion tree | ★★ | P0 | CP Handbook | LeetCode |
| Meet in the middle | split search space | ★★★★ | P2 | cp-algorithms | CF |
| Ternary search | unimodal functions (standalone) | ★★★ | P2 | cp-algorithms | CF |
| Constructive algorithms | build a valid answer | ★★★ | P1 | Codeforces EDU | CF |
| Interactive problems | query-response, adaptive | ★★★ | P2 | Codeforces EDU | CF |

## 1.5 Data Structures

| Topic | Subtopic | Diff | Pri | Best Resource | Practice |
|---|---|---|---|---|---|
| Stack / queue / deque | monotonic stack | ★★ | P0 | cp-algorithms | CSES |
| Sparse table | RMQ, idempotent | ★★★ | P1 | cp-algorithms | CSES |
| DSU | union by rank, path compression | ★★ | P0 | cp-algorithms | CSES |
| Fenwick (BIT) | point update, range query | ★★★ | P0 | cp-algorithms | CSES |
| Segment tree | build, query, update | ★★★ | P0 | cp-algorithms | CSES Range |
| Lazy propagation | range update | ★★★★ | P1 | cp-algorithms | CF |
| Segment tree beats / persistent | advanced | ★★★★ | P3 | cp-algorithms | CF |

## 1.6 Graphs

| Topic | Subtopic | Diff | Pri | Best Resource | Practice |
|---|---|---|---|---|---|
| Traversal | BFS, DFS | ★★ | P0 | cp-algorithms | CSES Graph |
| Shortest path | Dijkstra, Bellman-Ford, 0-1 BFS | ★★★ | P0 | cp-algorithms | CSES |
| All pairs | Floyd-Warshall | ★★ | P1 | cp-algorithms | CSES |
| MST | Kruskal, Prim | ★★★ | P0 | cp-algorithms | CSES |
| Topological sort | Kahn, DFS | ★★ | P0 | cp-algorithms | CSES |
| SCC | Tarjan, Kosaraju | ★★★★ | P1 | cp-algorithms | CF |
| Bridges & articulation | | ★★★★ | P2 | cp-algorithms | CF |
| Euler path/circuit | | ★★★ | P2 | cp-algorithms | CSES |
| Bipartite check | 2-coloring | ★★ | P1 | cp-algorithms | CSES |

## 1.7 Trees

| Topic | Subtopic | Diff | Pri | Best Resource | Practice |
|---|---|---|---|---|---|
| Tree basics | rooting, subtree size | ★★ | P0 | cp-algorithms | CSES Tree |
| LCA | binary lifting | ★★★ | P0 | cp-algorithms | CSES |
| Binary lifting | kth ancestor | ★★★ | P1 | cp-algorithms | CSES |
| Euler tour | subtree → range | ★★★ | P1 | cp-algorithms | CF |
| Small-to-large | merging | ★★★★ | P2 | cp-algorithms | CF |
| Heavy-Light Decomposition | path queries | ★★★★ | P2 | cp-algorithms | CF |
| Centroid decomposition | | ★★★★ | P3 | cp-algorithms | CF |
| Rerooting DP | | ★★★★ | P2 | USACO Guide | CF |

## 1.8 Dynamic Programming

| Topic | Subtopic | Diff | Pri | Best Resource | Practice |
|---|---|---|---|---|---|
| Basics | 1D, 2D, knapsack | ★★ | P0 | CP Handbook Ch.7 | CSES DP |
| Grid / paths | | ★★ | P0 | CSES | CSES |
| Subset / bitmask DP | TSP | ★★★ | P0 | cp-algorithms | CSES |
| DP on trees | | ★★★ | P0 | USACO Guide | CF |
| Digit DP | | ★★★★ | P1 | cp-algorithms | CF |
| DP optimization | prefix, D&C, CHT, Knuth | ★★★★ | P2 | cp-algorithms | CF |
| Interval / range DP | | ★★★ | P1 | USACO Guide | CF |
| Probability / expected DP | | ★★★★ | P2 | CP Handbook | CF |

## 1.9 Strings

| Topic | Subtopic | Diff | Pri | Best Resource | Practice |
|---|---|---|---|---|---|
| Hashing | polynomial, double hash | ★★★ | P0 | cp-algorithms | CSES String |
| KMP | prefix function | ★★★ | P0 | cp-algorithms | CSES |
| Z-function | | ★★★ | P1 | cp-algorithms | CF |
| Trie | | ★★ | P1 | cp-algorithms | CF |
| Aho-Corasick | multi-pattern | ★★★★ | P2 | cp-algorithms | CF |
| Suffix array | | ★★★★ | P2 | cp-algorithms | CF |
| Suffix automaton | | ★★★★ | P3 | cp-algorithms | CF |
| Manacher | palindromes | ★★★★ | P2 | cp-algorithms | CF |

## 1.10 Geometry · Game Theory · Advanced

| Topic | Subtopic | Diff | Pri | Best Resource | Practice |
|---|---|---|---|---|---|
| Geometry basics | cross/dot, orientation | ★★★ | P1 | cp-algorithms | CF |
| Convex hull | Graham/Andrew | ★★★★ | P2 | cp-algorithms | CF |
| Line sweep | | ★★★★ | P2 | cp-algorithms | CF |
| Game theory | Nim, Grundy/Sprague | ★★★ | P1 | cp-algorithms | CF |
| FFT / NTT | polynomial multiply | ★★★★ | P3 | cp-algorithms | CF |
| Max flow | Dinic, Edmonds-Karp | ★★★★ | P2 | cp-algorithms | CF |
| Min cut / matching | Hungarian, König | ★★★★ | P3 | cp-algorithms | CF |
| 2-SAT | implication graph + SCC | ★★★★ | P3 | cp-algorithms | CF |
| Expression parsing | shunting-yard, recursive descent | ★★★ | P2 | cp-algorithms | CF |

**CP practice ladders:** CSES Problem Set (do fully) · Codeforces problemset filtered by rating · USACO Guide (usaco.guide) · AtCoder Beginner Contests. **Contest cadence:** every Codeforces round + LeetCode weekly.

---

# PART 2 — MODERN C++
*Reference: cppreference.com · Books: Effective Modern C++ (Meyers), The C++ Programming Language (Stroustrup)*

## 2.1 Language Core

| Topic | Subtopic | Diff | Pri | Best Resource |
|---|---|---|---|---|
| Types & values | value categories (lvalue/rvalue/xvalue) | ★★ | P0 | cppreference |
| References | lvalue ref, const ref | ★★ | P0 | cppreference |
| auto & decltype | type deduction rules | ★★ | P0 | Effective Modern C++ Item 1-4 |
| const / constexpr | const-correctness | ★★ | P0 | cppreference |
| Scope & lifetime | RAII | ★★ | P0 | cppreference |

## 2.2 Memory & Object Model

| Topic | Subtopic | Diff | Pri | Best Resource |
|---|---|---|---|---|
| Stack vs heap | new/delete | ★★ | P0 | cppreference |
| Object layout | alignment, padding | ★★★ | P1 | cppreference |
| Smart pointers | unique_ptr, shared_ptr, weak_ptr | ★★★ | P0 | Effective Modern C++ Item 18-22 |
| RAII patterns | | ★★★ | P0 | cppreference |
| Rule of 0/3/5 | | ★★★ | P0 | cppreference |
| Placement new / allocators | | ★★★★ | P2 | cppreference |

## 2.3 Move Semantics & Templates

| Topic | Subtopic | Diff | Pri | Best Resource |
|---|---|---|---|---|
| Move semantics | rvalue refs, std::move | ★★★ | P0 | Effective Modern C++ Item 23-30 |
| Perfect forwarding | std::forward | ★★★★ | P1 | Effective Modern C++ |
| Copy elision / RVO | | ★★★ | P1 | cppreference |
| Templates | function & class templates | ★★★ | P0 | cppreference |
| Variadic templates | parameter packs | ★★★★ | P2 | cppreference |
| SFINAE / concepts (C++20) | | ★★★★ | P2 | cppreference |
| CRTP | | ★★★★ | P3 | cppreference |

## 2.4 STL (deep)

| Topic | Subtopic | Diff | Pri | Best Resource |
|---|---|---|---|---|
| Containers | vector, deque, list | ★★ | P0 | cppreference |
| Associative | map, set, unordered_* | ★★ | P0 | cppreference |
| Container adaptors | stack, queue, priority_queue | ★★ | P0 | cppreference |
| Iterators | categories, invalidation | ★★★ | P0 | cppreference |
| Algorithms | sort, lower_bound, accumulate, transform | ★★ | P0 | cppreference |
| Lambdas | captures, mutable, generic | ★★★ | P0 | Effective Modern C++ Item 31-34 |
| std::function / bind | | ★★★ | P1 | cppreference |
| Ranges (C++20) | views | ★★★★ | P2 | cppreference |

## 2.5 Concurrency in C++

| Topic | Subtopic | Diff | Pri | Best Resource |
|---|---|---|---|---|
| Threads | std::thread, join/detach | ★★★ | P0 | cppreference |
| Mutex & locks | lock_guard, unique_lock | ★★★ | P0 | cppreference |
| Condition variables | | ★★★★ | P1 | cppreference |
| Atomics | memory_order | ★★★★ | P1 (P0 for HFT) | cppreference |
| Futures / async | promise, packaged_task | ★★★ | P1 | cppreference |
| Memory model | happens-before | ★★★★ | P2 (P0 HFT) | Effective Modern C++ Item 40 |

---

# PART 3 — CS FUNDAMENTALS

## 3.1 Operating Systems *(OSTEP — ostep.org)*

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| Processes | creation, states, PCB | ★★ | P0 | OSTEP |
| Threads | user vs kernel | ★★ | P0 | OSTEP |
| Scheduling | FCFS, RR, MLFQ, CFS | ★★★ | P0 | OSTEP |
| Synchronization | locks, semaphores, monitors | ★★★ | P0 | OSTEP |
| Deadlock | detection, prevention | ★★★ | P0 | OSTEP |
| Memory | paging, segmentation, TLB | ★★★ | P0 | OSTEP |
| Virtual memory | page replacement | ★★★ | P0 | OSTEP |
| File systems | inodes, journaling | ★★★ | P1 | OSTEP |
| I/O | interrupts, DMA | ★★★ | P1 | OSTEP |

## 3.2 Networking *(Kurose & Ross)*

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| Model | OSI vs TCP/IP | ★ | P0 | Kurose |
| HTTP/HTTPS | methods, status, HTTP/2, HTTP/3 | ★★ | P0 | MDN + Kurose |
| TCP | handshake, flow/congestion control | ★★★ | P0 | Kurose |
| UDP | when/why | ★★ | P0 | Kurose |
| TLS | handshake, certs | ★★★ | P1 | Kurose |
| DNS | resolution, records | ★★ | P0 | Kurose |
| IP & routing | subnetting, NAT | ★★★ | P1 | Kurose |
| WebSockets | | ★★ | P1 | MDN |
| Load balancing | L4 vs L7 | ★★★ | P0 | System Design Primer |

## 3.3 DBMS *(CMU 15-445)*

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| Relational model | keys, normalization | ★★ | P0 | CMU 15-445 |
| SQL | joins, aggregation, window fns | ★★ | P0 | CMU 15-445 |
| Indexing | B+ tree, hash index | ★★★ | P0 | CMU 15-445 |
| Storage | pages, buffer pool | ★★★ | P1 | CMU 15-445 |
| Query execution | operators, join algos | ★★★ | P1 | CMU 15-445 |
| Query optimization | cost-based | ★★★★ | P2 | CMU 15-445 |
| Transactions | ACID | ★★★ | P0 | CMU 15-445 |
| Concurrency control | 2PL, MVCC | ★★★★ | P0 | CMU 15-445 |
| Recovery | WAL, ARIES | ★★★★ | P2 | CMU 15-445 |
| Isolation levels | anomalies | ★★★ | P0 | DDIA Ch.7 |
| Deadlocks | detection, prevention, ordering | ★★★ | P0 | CMU 15-445 |
| Connection pooling | pool sizing, why it matters | ★★★ | P0 | Backend roadmap 2026 |
| Query optimization (practical) | EXPLAIN, N+1 problem | ★★★ | P0 | use-the-index-luke.com |
| Sharding & partitioning | at DB level | ★★★★ | P1 | DDIA Ch.6 |

## 3.4 Linux

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| Shell | bash, pipes, redirection | ★★ | P0 | tldp.org / man |
| Processes | ps, top, kill, signals | ★★ | P0 | man pages |
| Files & perms | chmod, chown, links | ★★ | P0 | man pages |
| Text tools | grep, sed, awk | ★★★ | P1 | man pages |
| Networking tools | netstat, ss, tcpdump, curl | ★★★ | P1 | man pages |
| systemd | services | ★★★ | P2 | freedesktop docs |
| Performance | strace, perf, /proc | ★★★★ | P1 | Brendan Gregg blog |

---

# PART 4 — BACKEND & DISTRIBUTED SYSTEMS
*Core book: Designing Data-Intensive Applications (DDIA) — read cover to cover*

## 4.1 HTTP & Web Protocols (foundation — know this cold)

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| HTTP verbs | GET, POST, PUT, PATCH, DELETE, HEAD, OPTIONS | ★ | P0 | MDN |
| Idempotency & safety | which verbs are idempotent/safe | ★★ | P0 | MDN / Stripe blog |
| Status codes | 2xx, 3xx, 4xx, 5xx (know 200/201/204/301/400/401/403/404/409/422/429/500/502/503) | ★★ | P0 | MDN |
| Headers | content-type, cache-control, auth, cookies, CORS | ★★ | P0 | MDN |
| Request/response lifecycle | how a request travels client→server→DB→back | ★★ | P0 | MDN |
| Connection management | keep-alive, connection pooling | ★★★ | P1 | HTTP roadmap 2026 |
| HTTP/1.1 vs HTTP/2 | multiplexing, head-of-line blocking | ★★★ | P1 | web.dev |
| HTTP/3 (QUIC) | UDP-based, latency reduction | ★★★ | P2 | web.dev |
| Cookies & sessions | secure, httpOnly, sameSite | ★★ | P0 | MDN |
| CORS | preflight, allowed origins | ★★★ | P1 | MDN |
| WebSockets vs SSE vs polling | when to use each | ★★★ | P1 | MDN |

## 4.2 API & Service Design

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| REST | resources, verbs, status | ★★ | P0 | MDN / Roy Fielding |
| API versioning | URL vs header versioning | ★★ | P1 | System Design Primer |
| Pagination | offset vs cursor-based | ★★★ | P0 | Backend roadmap 2026 |
| Filtering & sorting | query params, avoid slow endpoints | ★★ | P0 | Backend roadmap 2026 |
| Error format | consistent error envelopes | ★★ | P0 | Stripe API docs |
| Webhooks | event delivery, retries, signature verify | ★★★ | P1 | Stripe docs |
| gRPC / protobuf | | ★★★ | P1 | grpc.io |
| GraphQL | | ★★★ | P2 | graphql.org |
| Idempotency | keys, retries, safe replays | ★★★ | P0 | Stripe blog |
| Rate limiting | token/leaky bucket | ★★★ | P0 | System Design Primer |
| Pagination at scale | keyset pagination | ★★★ | P1 | Backend roadmap 2026 |

## 4.3 Caching

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| Cache strategies | cache-aside, write-through/back | ★★★ | P0 | DDIA / System Design Primer |
| Eviction | LRU, LFU, TTL | ★★★ | P0 | redis.io |
| Cache invalidation | | ★★★★ | P0 | DDIA |
| CDN | edge caching | ★★ | P1 | System Design Primer |

## 4.4 Redis *(redis.io)*

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| Data types | string, hash, list, set, zset | ★★ | P0 | redis.io |
| Persistence | RDB, AOF | ★★★ | P1 | redis.io |
| Pub/Sub | | ★★ | P1 | redis.io |
| Expiry & eviction | | ★★★ | P0 | redis.io |
| Distributed lock | Redlock | ★★★★ | P1 | redis.io |
| Cluster | sharding, replication | ★★★★ | P1 | redis.io |
| Streams | | ★★★ | P2 | redis.io |

## 4.5 Kafka *(kafka.apache.org + Confluent docs)*

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| Concepts | topic, partition, offset | ★★★ | P0 | Confluent docs |
| Producers | acks, batching | ★★★ | P0 | Confluent docs |
| Consumers | groups, rebalancing | ★★★ | P0 | Confluent docs |
| Delivery guarantees | at-least/exactly-once | ★★★★ | P0 | DDIA Ch.11 |
| Replication | ISR, leader election | ★★★★ | P1 | Confluent docs |
| Ordering | per-partition | ★★★ | P0 | Confluent docs |
| Streams / Connect | | ★★★★ | P2 | Confluent docs |

## 4.6 Distributed Systems *(DDIA)*

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| Replication | leader/follower, multi-leader | ★★★★ | P0 | DDIA Ch.5 |
| Partitioning / sharding | hash, range, consistent hashing | ★★★★ | P0 | DDIA Ch.6 |
| Consistency | strong, eventual, causal | ★★★★ | P0 | DDIA Ch.5,9 |
| CAP & PACELC | | ★★★ | P0 | DDIA |
| Consensus | Paxos, Raft | ★★★★ | P1 | raft.github.io |
| Distributed transactions | 2PC, saga | ★★★★ | P1 | DDIA Ch.9 |
| Quorums | R+W>N | ★★★★ | P1 | DDIA |
| Clocks | logical, vector, Lamport | ★★★★ | P1 | DDIA Ch.8 |
| Failure detection | heartbeats, gossip | ★★★ | P2 | DDIA |
| Message queues | delivery, DLQ, backpressure | ★★★ | P0 | DDIA Ch.11 |

## 4.7 Docker · Kubernetes · Cloud

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| Docker | images, layers, volumes, networks | ★★★ | P0 | docs.docker.com |
| Dockerfile | multi-stage builds | ★★★ | P0 | docs.docker.com |
| K8s core | pod, deployment, service | ★★★★ | P1 | kubernetes.io |
| K8s config | configmap, secret, ingress | ★★★★ | P1 | kubernetes.io |
| K8s scaling | HPA, resource limits | ★★★★ | P2 | kubernetes.io |
| Cloud basics | compute, storage, IAM | ★★★ | P1 | AWS/GCP docs |
| Load balancers / autoscaling | | ★★★ | P1 | cloud docs |

## 4.8 Performance Engineering & Observability

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| Latency vs throughput | tail latency (p99) | ★★★ | P0 | DDIA Ch.1 |
| Profiling | CPU, memory, flame graphs | ★★★★ | P1 (P0 HFT) | Brendan Gregg |
| Benchmarking | load testing | ★★★ | P1 | — |
| Logging | structured logs | ★★ | P0 | — |
| Metrics | Prometheus, RED/USE method | ★★★ | P0 | prometheus.io |
| Tracing | distributed tracing | ★★★ | P1 | opentelemetry.io |
| Three pillars | metrics + logs + traces | ★★★ | P0 | opentelemetry.io |
| Four golden signals | latency, traffic, errors, saturation | ★★★ | P0 | Google SRE book |
| Low-latency (HFT) | cache lines, false sharing, lock-free, NUMA | ★★★★ | P0 (HFT) | Gregg / talks |

## 4.9 Authentication, Authorization & Security

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| AuthN vs AuthZ | difference (know cold — common interview Q) | ★★ | P0 | Backend roadmap 2026 |
| Sessions vs tokens | server session vs stateless JWT | ★★★ | P0 | jwt.io |
| JWT | structure, signing, expiry, refresh tokens | ★★★ | P0 | jwt.io |
| OAuth 2.0 / OIDC | authorization code flow, scopes | ★★★★ | P0 | oauth.net |
| Password hashing | bcrypt, argon2, salting (never plain/MD5) | ★★★ | P0 | OWASP |
| RBAC / ABAC | role vs attribute-based access | ★★★ | P0 | — |
| API keys & mTLS | service-to-service auth | ★★★ | P1 | — |
| OWASP Top 10 | injection, XSS, CSRF, SSRF, broken auth | ★★★ | P0 | owasp.org |
| Input validation | sanitization, parameterized queries | ★★★ | P0 | OWASP |
| Secrets management | vaults, env, key rotation | ★★★ | P1 | — |
| TLS / HTTPS | handshake, cert chain, HSTS | ★★★ | P0 | — |
| Rate limiting & abuse | per-user/IP, DDoS basics | ★★★ | P0 | System Design Primer |

## 4.10 Async Processing & Messaging Patterns

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| Why async | keep work out of the request path | ★★★ | P0 | Backend roadmap 2026 |
| Job queues | producers, workers, task queues | ★★★ | P0 | Backend roadmap 2026 |
| Retries | exponential backoff, jitter | ★★★ | P0 | AWS Builders' Library |
| Dead letter queues | poison messages | ★★★ | P1 | Confluent docs |
| Backpressure | flow control under load | ★★★★ | P1 | DDIA |
| Delayed / scheduled jobs | cron, delayed tasks | ★★ | P1 | — |
| Idempotent consumers | exactly-once effect | ★★★★ | P0 | DDIA Ch.11 |
| Event-driven architecture | pub/sub, event sourcing, CQRS | ★★★★ | P1 | DDIA / Martin Fowler |
| Outbox pattern | reliable event publishing | ★★★★ | P2 | microservices.io |

## 4.11 Microservices & Architecture Patterns

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| Monolith vs microservices | when to split, tradeoffs | ★★★ | P0 | microservices.io |
| API gateway | routing, auth, rate limit at edge | ★★★ | P0 | microservices.io |
| Service discovery | registry, DNS-based | ★★★ | P1 | microservices.io |
| Circuit breaker | fail fast, fallback | ★★★★ | P0 | microservices.io |
| Bulkhead & timeout | isolation, graceful degradation | ★★★ | P1 | Release It! (book) |
| Saga pattern | distributed transactions | ★★★★ | P1 | microservices.io |
| Sidecar / service mesh | Istio/Envoy concept | ★★★★ | P2 | — |
| Idempotency & retries | at service boundaries | ★★★ | P0 | Stripe blog |
| Config & feature flags | runtime toggles | ★★★ | P1 | — |

## 4.12 Reliability & SRE (Google's own framework)

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| SLI / SLO / Error budget | measure, target, allowance | ★★★ | P0 | Google SRE book (sre.google) |
| The "nines" | 99.9% = ~43 min/month downtime | ★★★ | P0 | Google SRE book |
| Burn rate alerting | multi-window (1h + 6h) | ★★★★ | P1 | Google SRE workbook |
| Postmortems | blameless, root cause | ★★ | P0 | Google SRE book |
| Deployment strategies | blue-green, canary, rolling | ★★★ | P0 | — |
| Feature flags | decouple deploy from release | ★★★ | P1 | — |
| Graceful degradation | fail soft, fallbacks | ★★★ | P0 | Google SRE book |
| Chaos / fault injection | resilience testing | ★★★★ | P2 | — |
| Capacity planning | headroom, load forecasting | ★★★ | P1 | Google SRE book |

## 4.13 Testing & Delivery

| Topic | Subtopic | Diff | Pri | Resource |
|---|---|---|---|---|
| Unit testing | isolation, mocking | ★★ | P0 | — |
| Integration testing | service + DB | ★★★ | P0 | — |
| Contract testing | consumer-driven contracts | ★★★ | P1 | Pact |
| Load / stress testing | k6, JMeter | ★★★ | P1 | k6.io |
| CI/CD | pipelines, automated deploy | ★★★ | P0 | — |
| Test pyramid | unit > integration > e2e | ★★ | P0 | Google Testing Blog |

---

# PART 5 — SYSTEM DESIGN (HLD)
*Books: Alex Xu Vol 1 & 2 · Free: System Design Primer*

## 5.1 Building Blocks (learn first)

| Topic | Pri | Resource |
|---|---|---|
| Load balancing (L4/L7) | P0 | System Design Primer |
| Caching strategies & CDN | P0 | Alex Xu Vol 1 |
| DB replication & sharding | P0 | DDIA |
| SQL vs NoSQL selection | P0 | Alex Xu Vol 1 |
| Message queues | P0 | Alex Xu Vol 1 |
| Consistent hashing | P0 | Alex Xu Vol 1 |
| Rate limiter design | P0 | Alex Xu Vol 1 |
| Unique ID generation | P0 | Alex Xu Vol 1 |
| Bloom filters | P1 | System Design Primer |
| Back-of-envelope estimation | P0 | Alex Xu Vol 1 |

## 5.2 Classic Design Problems

| Problem | Diff | Pri | Reference |
|---|---|---|---|
| TinyURL / URL shortener | ★★ | P0 | Alex Xu Vol 1 |
| Rate limiter | ★★★ | P0 | Alex Xu Vol 1 |
| Key-value store | ★★★★ | P1 | Alex Xu Vol 1 |
| Notification service | ★★★ | P0 | Alex Xu Vol 1 |
| News Feed (Instagram/Facebook) | ★★★★ | P0 | Alex Xu Vol 1 |
| Chat (WhatsApp/Discord) | ★★★★ | P0 | Alex Xu Vol 1 |
| Search autocomplete | ★★★ | P1 | Alex Xu Vol 1 |
| **YouTube / video streaming** | ★★★★ | **P0** | Alex Xu Vol 1 |
| Netflix | ★★★★ | P0 | Alex Xu / primer |
| Instagram Reels / short video | ★★★★ | P0 | Alex Xu Vol 2 |
| Google Drive / Dropbox | ★★★★ | P0 | Alex Xu Vol 1 |
| Uber / ride-sharing | ★★★★ | P0 | Alex Xu Vol 2 |
| Web crawler | ★★★ | P1 | Alex Xu Vol 1 |
| Distributed cache | ★★★★ | P1 | primer |
| Distributed job scheduler | ★★★★ | P1 | Alex Xu Vol 2 |
| Ad click aggregation / analytics | ★★★★ | P1 | Alex Xu Vol 2 |
| Recommendation system | ★★★★ | P1 | Alex Xu Vol 2 |
| Video processing pipeline | ★★★★ | P1 | Alex Xu Vol 2 |
| Payment system | ★★★★ | P1 | Alex Xu Vol 2 |
| Stock exchange / matching engine | ★★★★ | P1 (P0 HFT) | Alex Xu Vol 2 |

**Framework for every problem:** requirements (functional + non-functional) → estimation → API design → high-level diagram → data model → deep dives → bottlenecks → tradeoffs.

---

# PART 6 — LOW LEVEL DESIGN (LLD)
*Refactoring Guru + "Head First Design Patterns"*

## 6.1 OOP & Principles

| Topic | Pri | Resource |
|---|---|---|
| OOP pillars | P0 | Refactoring Guru |
| SOLID principles | P0 | Refactoring Guru |
| DRY / KISS / YAGNI | P0 | — |
| Composition over inheritance | P0 | Refactoring Guru |

## 6.2 Design Patterns

| Category | Patterns | Pri | Resource |
|---|---|---|---|
| Creational | Singleton, Factory, Abstract Factory, Builder, Prototype | P0 | Refactoring Guru |
| Structural | Adapter, Decorator, Facade, Proxy, Composite, Bridge, Flyweight | P0 | Refactoring Guru |
| Behavioral | Observer, Strategy, Command, State, Iterator, Template Method, Chain of Responsibility, Mediator | P0 | Refactoring Guru |

## 6.3 LLD Interview Problems

| Problem | Pri |
|---|---|
| Parking lot | P0 |
| Elevator system | P0 |
| BookMyShow / ticket booking | P0 |
| Splitwise | P0 |
| Vending machine | P1 |
| Rate limiter (OO) | P1 |
| Logging framework | P1 |
| Chess / tic-tac-toe | P1 |
| Cache (LRU with OO) | P0 |
| Notification system | P1 |
| Food delivery (Zomato) | P1 |
| Snake & ladder | P2 |

---

# PART 7 — GOOGLE INTERVIEW PREP

## 7.1 Coding Rounds

| Area | What | Pri | Resource |
|---|---|---|---|
| DSA patterns | arrays, strings, trees, graphs, DP | P0 | NeetCode 150 / LeetCode |
| Problem-solving out loud | communicate approach | P0 | mock interviews |
| Edge cases & testing | | P0 | — |
| Complexity analysis | always state it | P0 | — |
| Blind 75 / NeetCode 150 | curated set | P0 | neetcode.io |

## 7.2 Behavioral (Googleyness & Leadership)

| Topic | Pri | Resource |
|---|---|---|
| STAR method | P0 | — |
| Conflict / failure stories | P0 | prep 6-8 stories |
| "Tell me about a hard bug" | P0 | use RentoMojo work |
| Ownership / impact stories | P0 | — |
| Questions to ask interviewer | P1 | — |

## 7.3 Machine Coding / Practical

| Topic | Pri |
|---|---|
| Build working feature in 60-90 min | P1 |
| Clean, testable, extensible code | P1 |
| LLD applied live | P1 |

## 7.4 Resume & Logistics

| Item | Status |
|---|---|
| One-page resume, quantified bullets | in progress |
| Referral (Amit) | secured |
| 3 role choices within a month | pending |
| Mock interviews (weekly) | ongoing |
| LeetCode/Codeforces contest cadence | ongoing |

---

# 12-MONTH PHASING (suggested)

| Months | Primary focus | Secondary |
|---|---|---|
| 1–2 | CP foundations→data structures + C++ core + resume/referral | daily LeetCode |
| 3–4 | CP graphs/trees/DP + OS + DBMS | weekly contests → Specialist |
| 5–6 | CP strings/advanced + Networking + Redis/Kafka | System design building blocks |
| 7–8 | DDIA + distributed systems + Docker/K8s | HLD classic problems |
| 9–10 | System design deep + LLD patterns/problems | mock interviews start |
| 11–12 | Interview grind: NeetCode 150 + behavioral + mocks | apply via referral, target Expert |

---

*Pull topics from here into the Elite Engineer OS sheet to track confidence, revision (D1/D3/D7/D15/D30), and status. This doc is the map; the sheet is the odometer.*
