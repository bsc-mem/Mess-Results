<div align="center">
<img src="doc/logo.png" alt="Mess logo" width="140">
<h1>Mess Results</h1>
<p>Measured memory bandwidth–latency curves for consumer and HPC systems.</p>
<p><a href="#consumer-curves">Consumer curves</a> · <a href="#hpc-curves">HPC curves</a> · <a href="#system-index">System index</a> · <a href="#using-the-results">Using the results</a></p>
</div>

| Configurations | Systems | Consumer | HPC |
| :---: | :---: | :---: | :---: |
| **38** | **17** | 8 configurations | 30 configurations |

Results measured with [Mess](https://github.com/bsc-mem/Mess). Click a curve for recorded machine specs and PDF, CSV, and JSON downloads.

## System index

### Consumer

| System | Available configurations |
| --- | --- |
| [AMD Ryzen 7 5700X3D](#consumer-amd-ryzen-7-5700x3d) | Default |
| [Apple MacBook Air M1](#consumer-apple-m1-base-macbook-air) | M1 · MacBook Air |
| [Apple MacBook Air M2](#consumer-apple-m2-base-macbook-air) | M2 · MacBook Air |
| [Intel Core i5-8600K](#consumer-intel-core-i5-8600k) | 2133 MT/s · 16 GB; 2666 MT/s · 8 GB; 3200 MT/s · 16 GB |
| [Intel Core i7-1185G7](#consumer-intel-core-i7-1185g7) | 3733 MT/s · 16 GB |
| [Intel Core i7-1265U](#consumer-intel-core-i7-1265u) | Default |

### HPC

| System | Processor | Available configurations |
| --- | --- | --- |
| [CTE-AMD](#hpc-cte-amd) | AMD EPYC 7742 | DDR4 |
| [Intel-CLX](#hpc-intel-clx) | Intel Xeon Gold 5218 | DDR4 |
| [Fugaku](#hpc-fugaku) | Fujitsu A64FX | NEON · SVE |
| [NVIDIA Grace](#hpc-nvidia-grace) | NVIDIA Grace | Scalar · NEON Native / Pair · SVE / SVE128 / SVE Max |
| [Intel-EMR](#hpc-intel-emr) | Xeon Platinum 8568CXL | DDR5 · Prefetch on / off |
| [Intel-GNR](#hpc-intel-gnr) | Xeon 6980P | RDIMM · AVX2 / AVX512; MRDIMM · AVX2 |
| [Jülich](#hpc-julich) | Intel Xeon Max 9462 | DDR5 · HBM |
| [MN5 ACC](#hpc-mn5-mn5-acc-cpu) | Intel Xeon Platinum 8460Y+ | DDR5 |
| [MN5 ACC](#hpc-mn5-mn5-acc-gpu) | NVIDIA H100 | H100 |
| [MN5 GPP](#hpc-mn5-mn5-gpp) | Intel Xeon Platinum 8480+ | Regular / highmem · AVX2, AVX512, Scalar, SSE |
| [MN5 HBM](#hpc-mn5-mn5-hbm) | Intel Xeon Max 9480 | HBM · DDR5 · SNC DDR5 |

## Consumer curves

[Browse folders](Systems/Consumer/README.md) · [System index](#system-index)

### AMD Ryzen

<a id="consumer-amd-ryzen-7-5700x3d"></a>

#### AMD Ryzen 7 5700X3D

**3200 MT/s**

[<img src="Systems/Consumer/AMD/Ryzen-7-5700X3D/processed/memory_curves.png" alt="AMD Ryzen 7 5700X3D — 3200 MT/s" width="420">](Systems/Consumer/AMD/Ryzen-7-5700X3D/README.md)

### Apple Silicon

<a id="consumer-apple-m1-base-macbook-air"></a>

#### Apple MacBook Air M1

**Default**

[<img src="Systems/Consumer/Apple/M1/Base/MacBook-Air/processed/memory_curves.png" alt="Apple MacBook Air M1 — Default" width="420">](Systems/Consumer/Apple/M1/Base/MacBook-Air/README.md)

<a id="consumer-apple-m2-base-macbook-air"></a>

#### Apple MacBook Air M2

**Default**

[<img src="Systems/Consumer/Apple/M2/Base/MacBook-Air/processed/memory_curves.png" alt="Apple MacBook Air M2 — Default" width="420">](Systems/Consumer/Apple/M2/Base/MacBook-Air/README.md)

### Intel Core

<a id="consumer-intel-core-i5-8600k"></a>

#### Intel Core i5-8600K

| 2133MTs-16GB | 2666MTs-8GB | 3200MTs-16GB |
| :---: | :---: | :---: |
| [<img src="Systems/Consumer/Intel/Core-i5-8600K/2133MTs-16GB/processed/memory_curves.png" alt="Intel Core i5-8600K — 2133MTs-16GB" width="280">](Systems/Consumer/Intel/Core-i5-8600K/2133MTs-16GB/README.md) | [<img src="Systems/Consumer/Intel/Core-i5-8600K/2666MTs-8GB/processed/memory_curves.png" alt="Intel Core i5-8600K — 2666MTs-8GB" width="280">](Systems/Consumer/Intel/Core-i5-8600K/2666MTs-8GB/README.md) | [<img src="Systems/Consumer/Intel/Core-i5-8600K/3200MTs-16GB/processed/memory_curves.png" alt="Intel Core i5-8600K — 3200MTs-16GB" width="280">](Systems/Consumer/Intel/Core-i5-8600K/3200MTs-16GB/README.md) |

<a id="consumer-intel-core-i7-1185g7"></a>

#### Intel Core i7-1185G7

**3733MTs-16GB**

[<img src="Systems/Consumer/Intel/Core-i7-1185G7/3733MTs-16GB/processed/memory_curves.png" alt="Intel Core i7-1185G7 — 3733MTs-16GB" width="420">](Systems/Consumer/Intel/Core-i7-1185G7/3733MTs-16GB/README.md)

<a id="consumer-intel-core-i7-1265u"></a>

#### Intel Core i7-1265U

**Default**

[<img src="Systems/Consumer/Intel/Core-i7-1265U/processed/memory_curves.png" alt="Intel Core i7-1265U — Default" width="420">](Systems/Consumer/Intel/Core-i7-1265U/README.md)

## HPC curves

[Browse folders](Systems/HPC/README.md) · [System index](#system-index)

<a id="hpc-cte-amd"></a>

### CTE-AMD — AMD EPYC 7742

**DDR4 · 3200 MT/s**

[<img src="Systems/HPC/CTE-AMD/processed/memory_curves.png" alt="CTE-AMD — AMD EPYC 7742 — DDR4 · 3200 MT/s" width="420">](Systems/HPC/CTE-AMD/README.md)

<a id="hpc-intel-clx"></a>

### Intel-CLX — Intel Xeon Gold 5218

**DDR4 · 2933 MT/s**

[<img src="Systems/HPC/Intel-CLX/processed/memory_curves.png" alt="Intel-CLX — Intel Xeon Gold 5218 — DDR4 · 2933 MT/s" width="420">](Systems/HPC/Intel-CLX/README.md)

<a id="hpc-fugaku"></a>

### Fugaku — Fujitsu A64FX

| NEON | SVE |
| :---: | :---: |
| [<img src="Systems/HPC/Fugaku/neon/processed/memory_curves.png" alt="Fugaku — Fujitsu A64FX — NEON" width="280">](Systems/HPC/Fugaku/neon/README.md) | [<img src="Systems/HPC/Fugaku/sve/processed/memory_curves.png" alt="Fugaku — Fujitsu A64FX — SVE" width="280">](Systems/HPC/Fugaku/sve/README.md) |

<a id="hpc-nvidia-grace"></a>

### NVIDIA Grace

| SCALAR | NEON_NATIVE | NEON_PAIR |
| :---: | :---: | :---: |
| [<img src="Systems/HPC/NVIDIA-Grace/SCALAR/processed/memory_curves.png" alt="NVIDIA Grace — SCALAR" width="280">](Systems/HPC/NVIDIA-Grace/SCALAR/README.md) | [<img src="Systems/HPC/NVIDIA-Grace/NEON_NATIVE/processed/memory_curves.png" alt="NVIDIA Grace — NEON_NATIVE" width="280">](Systems/HPC/NVIDIA-Grace/NEON_NATIVE/README.md) | [<img src="Systems/HPC/NVIDIA-Grace/NEON_PAIR/processed/memory_curves.png" alt="NVIDIA Grace — NEON_PAIR" width="280">](Systems/HPC/NVIDIA-Grace/NEON_PAIR/README.md) |

| SVE | SVE128 | SVE_MAX |
| :---: | :---: | :---: |
| [<img src="Systems/HPC/NVIDIA-Grace/SVE/processed/memory_curves.png" alt="NVIDIA Grace — SVE" width="280">](Systems/HPC/NVIDIA-Grace/SVE/README.md) | [<img src="Systems/HPC/NVIDIA-Grace/SVE128/processed/memory_curves.png" alt="NVIDIA Grace — SVE128" width="280">](Systems/HPC/NVIDIA-Grace/SVE128/README.md) | [<img src="Systems/HPC/NVIDIA-Grace/SVE_MAX/processed/memory_curves.png" alt="NVIDIA Grace — SVE_MAX" width="280">](Systems/HPC/NVIDIA-Grace/SVE_MAX/README.md) |

<a id="hpc-intel-emr"></a>

### Intel EMR — Xeon Platinum 8568CXL

| DDR / prefetch off | DDR / prefetch on |
| :---: | :---: |
| [<img src="Systems/HPC/Intel-EMR/DDR/prefetch-off/processed/memory_curves.png" alt="Intel EMR — Xeon Platinum 8568CXL — DDR / prefetch off" width="280">](Systems/HPC/Intel-EMR/DDR/prefetch-off/README.md) | [<img src="Systems/HPC/Intel-EMR/DDR/prefetch-on/processed/memory_curves.png" alt="Intel EMR — Xeon Platinum 8568CXL — DDR / prefetch on" width="280">](Systems/HPC/Intel-EMR/DDR/prefetch-on/README.md) |

<a id="hpc-intel-gnr"></a>

### Intel GNR — Xeon 6980P

| MRDIMM / AVX2 | RDIMM / AVX2 | RDIMM / AVX512 |
| :---: | :---: | :---: |
| [<img src="Systems/HPC/Intel-GNR/MRDRIMMS/AVX2/processed/memory_curves.png" alt="Intel GNR — Xeon 6980P — MRDIMM / AVX2" width="280">](Systems/HPC/Intel-GNR/MRDRIMMS/AVX2/README.md) | [<img src="Systems/HPC/Intel-GNR/RDIMMS/AVX2/processed/memory_curves.png" alt="Intel GNR — Xeon 6980P — RDIMM / AVX2" width="280">](Systems/HPC/Intel-GNR/RDIMMS/AVX2/README.md) | [<img src="Systems/HPC/Intel-GNR/RDIMMS/AVX512/processed/memory_curves.png" alt="Intel GNR — Xeon 6980P — RDIMM / AVX512" width="280">](Systems/HPC/Intel-GNR/RDIMMS/AVX512/README.md) |

<a id="hpc-julich"></a>

### Jülich — Intel Xeon Max 9462

| DDR5 | HBM |
| :---: | :---: |
| [<img src="Systems/HPC/Jülich/Intel-Xeon-Max-9462/DDR5/processed/memory_curves.png" alt="Jülich — Intel Xeon Max 9462 — DDR5" width="280">](Systems/HPC/Jülich/Intel-Xeon-Max-9462/DDR5/README.md) | [<img src="Systems/HPC/Jülich/Intel-Xeon-Max-9462/HBM/processed/memory_curves.png" alt="Jülich — Intel Xeon Max 9462 — HBM" width="280">](Systems/HPC/Jülich/Intel-Xeon-Max-9462/HBM/README.md) |

<a id="hpc-mn5-mn5-acc-cpu"></a>

### MN5 ACC — Intel Xeon Platinum 8460Y+

**DDR5 · 4800 MT/s**

[<img src="Systems/HPC/MN5/MN5-ACC/CPU/processed/memory_curves.png" alt="MN5 ACC — Intel Xeon Platinum 8460Y+ — DDR5 · 4800 MT/s" width="420">](Systems/HPC/MN5/MN5-ACC/CPU/README.md)

<a id="hpc-mn5-mn5-acc-gpu"></a>

### MN5 ACC — NVIDIA H100

**H100**

[<img src="Systems/HPC/MN5/MN5-ACC/GPU/processed/memory_curves.png" alt="MN5 ACC — NVIDIA H100 — H100" width="420">](Systems/HPC/MN5/MN5-ACC/GPU/README.md)

<a id="hpc-mn5-mn5-gpp"></a>

### MN5 GPP — Intel Xeon Platinum 8480+

| highmem / AVX2 | highmem / AVX512 |
| :---: | :---: |
| [<img src="Systems/HPC/MN5/MN5-GPP/highmem/AVX2/processed/memory_curves.png" alt="MN5 GPP — Intel Xeon Platinum 8480+ — highmem / AVX2" width="280">](Systems/HPC/MN5/MN5-GPP/highmem/AVX2/README.md) | [<img src="Systems/HPC/MN5/MN5-GPP/highmem/AVX512/processed/memory_curves.png" alt="MN5 GPP — Intel Xeon Platinum 8480+ — highmem / AVX512" width="280">](Systems/HPC/MN5/MN5-GPP/highmem/AVX512/README.md) |

| highmem / SCALAR | highmem / SSE |
| :---: | :---: |
| [<img src="Systems/HPC/MN5/MN5-GPP/highmem/SCALAR/processed/memory_curves.png" alt="MN5 GPP — Intel Xeon Platinum 8480+ — highmem / SCALAR" width="280">](Systems/HPC/MN5/MN5-GPP/highmem/SCALAR/README.md) | [<img src="Systems/HPC/MN5/MN5-GPP/highmem/SSE/processed/memory_curves.png" alt="MN5 GPP — Intel Xeon Platinum 8480+ — highmem / SSE" width="280">](Systems/HPC/MN5/MN5-GPP/highmem/SSE/README.md) |

| regular / AVX2 | regular / AVX512 |
| :---: | :---: |
| [<img src="Systems/HPC/MN5/MN5-GPP/regular/AVX2/processed/memory_curves.png" alt="MN5 GPP — Intel Xeon Platinum 8480+ — regular / AVX2" width="280">](Systems/HPC/MN5/MN5-GPP/regular/AVX2/README.md) | [<img src="Systems/HPC/MN5/MN5-GPP/regular/AVX512/processed/memory_curves.png" alt="MN5 GPP — Intel Xeon Platinum 8480+ — regular / AVX512" width="280">](Systems/HPC/MN5/MN5-GPP/regular/AVX512/README.md) |

| regular / SCALAR | regular / SSE |
| :---: | :---: |
| [<img src="Systems/HPC/MN5/MN5-GPP/regular/SCALAR/processed/memory_curves.png" alt="MN5 GPP — Intel Xeon Platinum 8480+ — regular / SCALAR" width="280">](Systems/HPC/MN5/MN5-GPP/regular/SCALAR/README.md) | [<img src="Systems/HPC/MN5/MN5-GPP/regular/SSE/processed/memory_curves.png" alt="MN5 GPP — Intel Xeon Platinum 8480+ — regular / SSE" width="280">](Systems/HPC/MN5/MN5-GPP/regular/SSE/README.md) |

<a id="hpc-mn5-mn5-hbm"></a>

### MN5 HBM — Intel Xeon Max 9480

| DDR5 | SNC / DDR5 | HBM |
| :---: | :---: | :---: |
| [<img src="Systems/HPC/MN5/MN5-HBM/DDR5/processed/memory_curves.png" alt="MN5 HBM — Intel Xeon Max 9480 — DDR5" width="280">](Systems/HPC/MN5/MN5-HBM/DDR5/README.md) | [<img src="Systems/HPC/MN5/MN5-HBM/SNC/DDR5/processed/memory_curves.png" alt="MN5 HBM — Intel Xeon Max 9480 — SNC / DDR5" width="280">](Systems/HPC/MN5/MN5-HBM/SNC/DDR5/README.md) | [<img src="Systems/HPC/MN5/MN5-HBM/HBM/processed/memory_curves.png" alt="MN5 HBM — Intel Xeon Max 9480 — HBM" width="280">](Systems/HPC/MN5/MN5-HBM/HBM/README.md) |

## Using the results

- **CSV / JSON:** processed curve data for analysis and simulation.
- **PDF / PNG:** plots for viewing and reuse.
- **Units:** bandwidth in GB/s and latency in ns. Run READMEs document the machine and recorded configuration.

This collection contains multisequential results. Raw measurement logs are omitted to keep downloads compact.

## Contribute

Add a system or chip variant with [Mess](https://github.com/bsc-mem/Mess) results in CSV, JSON, PDF, and PNG. Include the machine model, chip, RAM capacity, OS, and run configuration in a short README.

## Citation

Please cite [A Mess of Memory System Benchmarking, Simulation and Application Profiling (MICRO 2024)](https://ieeexplore.ieee.org/document/10764561).

[Mess](https://github.com/bsc-mem/Mess) · [Mess Simulator](https://github.com/bsc-mem/Mess-simulator) · [Mess-Paraver](https://github.com/bsc-mem/Mess-Paraver)
