# references
Reference List for RISC-V

本仓库维护与labeled risv-v相关的参考资料信息。

## 学术论文
  1. [Hardware Execution Throttling for Multi-core Resource Management , USENIX ATC 09](http://static.usenix.org/events/usenix09/tech/full_papers/zhang/zhang_html/)
  1. Zihao Yu, et al., Labeled RISC-V: A New Perspective on Software-Defined Architecture [slides](https://riscv.org/wp-content/uploads/2017/05/Tue0930am-Labeled-RISC-V-Yu.pdf) , [paper](https://carrv.github.io/papers/yu-labeled_riscv-carrv2017.pdf) , RISCV workshop 2017 autumn
  1. David Lo, et al., [Heracles: Improving Resource Efficiency at Scale](http://csl.stanford.edu/~christos/publications/2015.heracles.isca.pdf) , ISCA 2015
  1. George Prekas, et al., [ZygOS: Achieving Low Tail Latency for Microsecond-scale Networked Tasks](https://infoscience.epfl.ch/record/231395/files/sosp17-final278.pdf) , SOSP 2017
  1. L. Ravindranath et al., [Timecard: Controlling User-Perceived Delays in Server-Based Mobile Applications](http://delivery.acm.org/10.1145/2530000/2522717/p85-ravindranath.pdf), SOSP, 2013.
  1. L. Albert Greenberg, [SDN for the Cloud](http://conferences.sigcomm.org/sigcomm/2015/pdf/papers/keynote.pdf), SIGCOMM Keynote, 2015.
  1. J. M. Kaplan, W. Forrest, and N. Kindler. [Revolutionizing data center energy efficiency](https://www.sallan.org/pdf-docs/McKinsey_Data_Center_Efficiency.pdf). McKinsey & Company, 2008.
  1. Huan Liu, [A Measurement Study of Server Utilization in Public Clouds](https://048744ef-a-62cb3a1a-s-sites.googlegroups.com/site/huanliu/cgc.pdf), 2011.
  1. J. Dean,“[Achieving Rapid Response Times in Large Online Services](https://static.googleusercontent.com/media/research.google.com/zh-CN//people/jeff/Berkeley-Latency-Mar2012.pdf)”, talk at Berkeley, 2012.
  1. L. Barrosa, J.Clidaras, U. Holzle, [The Datacenter as a Computer (2nd Edition)](http://www.morganclaypool.com/doi/abs/10.2200/S00516ED2V01Y201306CAC024), July, 2013.
  1. R. Kapoor et al. [Chronos: Predictable for Data Center Low Latency Applications](https://pdfs.semanticscholar.org/13b2/6d008210fffeb8a77c9e90f1ff837523c536.pdf), SOCC, 2012.
  1. Melanie Kambadur et al., “[Measuring Interference Between Live Datacenter Applications](https://pdfs.semanticscholar.org/e4bd/3f30e258a6048e18499176fa01cd1a508864.pdf)”, SC'11, 2011
  1. [Heterogeneity and Dynamicity of Clouds at Scale: Google Trace Analysis](http://www.istc-cc.cmu.edu/publications/papers/2012/googletrace-socc2012.pdf) SOCC 2012
  1. Jeff Dean, [Software Engineering Advice from Building Large-Scale Distributed Systems](http://prof.ict.ac.cn/DComputing/uploads/2013/DC_3_1_stanford-295-talk.pdf) 2016
  1. T. Chen et al., [Statistical Performance Comparisons of Computers](http://parsec.cs.princeton.edu/publications/chen14ieeetc.pdf), HPCA 2012.
  1. D. Krushevskaja and M.Sandler, [Understanding Latency Variations of Black Box Services](http://telemedicina.unifesp.br/pub/Events/2013-05%20-%20WWW2013/www2013/www2013.org/proceedings/p703.pdf), WWW 2013.
  1. http://www.gartner.com/newsroom/id/1472714.
  1. [FreeBSD/RISC-V and Device Drivers BSDTW2017](https://bsdtw.org/slides/BSDTW2017-D2-3-Ruslan.pdf)

 ### CACHE隔离
  1. [A Survey of Techniques for Cache Partitioning in Multicore Processors, ACM Computing Surveys 2017](https://www.researchgate.net/publication/314352438_A_Survey_of_Techniques_for_Cache_Partitioning_in_Multicore_Processors)
  1. [SWAP: Effective Fine-Grain Management of Shared Last-Level Caches with Minimum Hardware Support, HPCA17](http://www.csl.cornell.edu/~xiaodong/docs/SWAP.pdf)
  1. [Quasar: Resource-Efficient and QoS-Aware Cluster Management](http://www.csl.cornell.edu/~delimitrou/papers/2014.asplos.quasar.pdf)
  1. [Cuanta: quantifying effects of shared on-chip resource interference for consolidated virtual machines](https://pdfs.semanticscholar.org/8242/f42f077b59ff239e8cab19b99d94c190c608.pdf)
  1. [Reconciling High Server Utilization and Sub-millisecond Quality-of-Service](https://pdfs.semanticscholar.org/6d44/790b6d952eff28f302998e8121f90786e3ff.pdf)
  1. [Increasing Utilization in Modern Warehouse-Scale Computers Using Bubble-Up](http://web.eecs.umich.edu/~profmars/wp-content/papercite-data/pdf/mars12ieeemicro.pdf)
  1. [Scalable and Efficient Fine-Grained Cache Partitioning with Vantage](https://pdfs.semanticscholar.org/db1a/96c6e06385c1b93c912ae77aab8cf4c1b520.pdf)
  1. [A Hardware Evaluation of Cache Partitioning to Improve Utilization and Energy-efficiency While Preserving Responsiveness](http://people.eecs.berkeley.edu/~hcook/papers/ISCA13_Henry_Cook.pdf)
  1. [QoS Policies and Architecture for Cache/Memory in CMP Platforms](https://pdfs.semanticscholar.org/31c1/ebd6214a6146f2739fb81bf560229f413c91.pdf)
  1. [Utility-based cache partitioning: A low-overhead, high-performance, runtime mechanism to partition shared caches](http://tusharkrishna.ece.gatech.edu/wp-content/uploads/sites/175/2015/08/MICRO-2006-Qureshi-DynamicSetSampling.pdf)
  1. [Gaining insights into multicore cache partitioning: Bridging the gap between simulation and real systems](http://home.eng.iastate.edu/~zzhang/publications/tr08-hpca-multicore_cache.pdf)
  1. [1Q-Clouds: Managing Performance Interference Effects for QoS-Aware Clouds](http://seelab.ucsd.edu/mobile/related_papers/qClouds.pdf)

 ### 内存带宽隔离
  1. [QoS Policies and Architecture for Cache/Memory in CMP Platforms](https://pdfs.semanticscholar.org/31c1/ebd6214a6146f2739fb81bf560229f413c91.pdf)
  1. [A QoS-aware Memory Controller for Dynamically Balancing GPU and CPU Bandwidth Use in an MPSoC](https://lph.ece.utexas.edu/merez/uploads/MattanErez/cpugpumc_dac12.pdf)
  1. [Reducing Memory Interference in Multicore Systems via Application-aware Memory Channel Partitioning](https://users.ece.cmu.edu/~lsubrama/pubs/micro2011_mcp.pdf)
  1. [A Case for NUMA-aware Contention Management on Multicore Systems](http://ece.ubc.ca/~sasha/papers/usenix-numa.pdf)
  1. [The impact of memory subsystem resource sharing on datacenter applications](http://web.eecs.umich.edu/~profmars/wp-content/papercite-data/pdf/tang11isca.pdf)

### 调度相关
 1. [The Linux Scheduler: A Decade of Wasted Cores](https://www.ece.ubc.ca/~sasha/papers/eurosys16-final29.pdf)
 1. [Reconciling High Server Utilization and Sub-millisecond Quality-of-Service](http://csl.stanford.edu/~christos/publications/2014.mutilate.eurosys.pdf)
 1. [Borrowed-Virtual-Time (BVT) scheduling: supporting latency-sensitive threads in a general-purpose scheduler](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.131.6844&rep=rep1&type=pdf)
 1. [Cache-Guided Scheduling: Exploiting Caches to Maximize Locality in Graph Processing, AGP 2017](http://people.csail.mit.edu/sanchez/papers/2017.cgs.agp.pdf)

## 技术报告
  1. [Documentation for RISC-V Spike](https://github.com/poweihuang17/Documentation_Spike)
  1. [blog of various RISC-V ports(linux/gcc/glibc...) from Palmer Dabbelt](https://www.sifive.com/blog/2017/08/07/all-aboard-part-0-introduction/)

## perf tools
  1. [Linux Performance Tools](http://www.brendangregg.com/linuxperf.html)
  1. [perf tutorial](https://perf.wiki.kernel.org/index.php/Tutorial)
  1. [perf examples](http://www.brendangregg.com/perf.html)
  1. [Perf Tool: Performance Analysis Tool for Linux](http://lacasa.uah.edu/portal/Upload/tutorials/perf.tool/PerfTool.pdf)
  1. [Linux 性能诊断 perf使用指南](https://yq.aliyun.com/articles/65255)
  1. [Linux 效能分析工具: Perf](http://wiki.csie.ncku.edu.tw/embedded/perf-tutorial)

## benchmarks
  1. [Treadmill: Attributing the Source of Tail Latency through Precise Load Testing and Statistical Inference](http://web.eecs.umich.edu/~yunqi/pdf/zhang2016treadmill.pdf)
  1. [TailBench: A Benchmark Suite and Evaluation Methodology for Latency-Critical Applications](http://tailbench.csail.mit.edu/)
  1. [sysbench:Scriptable database and system performance benchmark](https://github.com/akopytov/sysbench)
  1. [hackbench − scheduler benchmark/stress test](https://man.cx/hackbench)
  1. [LLCbench - Low Level Architectural Characterization Benchmark Suite](http://icl.cs.utk.edu/llcbench/)
  1. [HPC Challenge Benchmark](http://icl.cs.utk.edu/hpcc/)
  1. [ZSim: Fast and Accurate Microarchitectural Simulation of Thousand-Core Systems](http://people.csail.mit.edu/sanchez/papers/2013.zsim.isca.pdf)

## 代码仓库
  1. [labeled riscv](http://github.com/LvNA-system/labeled-RISC-V)
  1. [educational microarchitectures for risc-v isa](https://github.com/ucb-bar/riscv-sodor)

## News
  1. [CNRV](https://cnrv.io/)

## 其他资源
  1. [resrouce from CNRV](https://github.com/cnrv/home/blob/master/resource.md)
  1. [papers from CNRV](https://github.com/cnrv/home/blob/master/papers.md)
