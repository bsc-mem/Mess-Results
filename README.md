
<div align="center">
    <img src="doc/logo.png" alt="Mess Benchmark Logo" width="200">
    <h1>Mess Benchmark Results Repository</h1>
    <p>
        <b>Memory System Bandwidth-Latency Curves for Modern Architectures</b><br>
        <a href="https://github.com/bsc-mem/Mess-2.0">Mess Benchmark 2.0</a> &mdash; A multiplatform benchmark for holistic, close-to-hardware memory system characterization.
    </p>
</div>

---

## About This Repository

This repository collects and organizes the results of running <b>Mess Benchmark</b> on a variety of systems. Each system folder contains bandwidth-latency curves and processed data, generated using the official Mess workflow.

Mess Benchmark is a multiplatform benchmark designed to provide a holistic, detailed, and close-to-hardware view of memory system performance through bandwidth-latency curves. It is the successor to the original [Mess Benchmark](https://github.com/bsc-mem/Mess-Benchmark) (now deprecated), with improved usability and portability.

**Reference:** [Mess Benchmark 2.0 on GitHub](https://github.com/bsc-mem/Mess-2.0)

> <b>MICRO 2024 Best Paper Runner-Up:</b> The Mess methodology was published at the 57th IEEE/ACM International Symposium on Microarchitecture.

---

## Table of Contents

- [Documentation](#documentation)
- [Motivation](#motivation)
- [Folder Structure](#folder-structure)
- [How to Contribute Results](#how-to-contribute-results)
- [Tools & Workflow](#tools--workflow)
- [Architecture Support](#architecture-support)
- [Citation](#citation)
- [References](#references)

---

## Documentation

Full documentation for Mess Benchmark is available in the [GitHub Wiki](https://github.com/bsc-mem/Mess-2.0/wiki).

---

## Motivation

Traditional memory benchmarks report isolated metrics such as peak bandwidth or idle latency, which often fail to capture how memory systems behave under realistic workloads. Mess addresses this limitation by characterizing memory performance through bandwidth-latency curves that cover the full range of memory traffic intensity, from unloaded to fully saturated.

This approach reveals critical insights:

- Memory writes degrade performance significantly compared to reads
- Systems typically saturate at 70-90% of theoretical maximum bandwidth
- Latency ranges from 85-130ns when idle to 200-600ns+ under saturation

Mess provides a holistic, close-to-hardware view of memory system behavior, enabling researchers and engineers to understand real-world performance characteristics that standard benchmarks miss.

---

## Folder Structure

Each system's results are organized as follows:

```
SystemFolder
├── local
│   ├── bw/
│   ├── lat/
│   ├── processed/
│   └── plotter.txt
└── remote
        ├── bw/
        ├── lat/
        ├── processed/
        └── plotter.txt
```

**See [Systems/MN5/MN5-GPP](Systems/MN5/MN5-GPP) for a detailed example.**

---

## How to Contribute Results

1. Run Mess Benchmark 2.0 on your system. See [Mess 2.0 Quick Start](https://github.com/bsc-mem/Mess-2.0#quick-start).
2. Use the official plotter (`utils/plotter.py`) to generate processed results (CSV, JSON, PNG, PDF).
3. Place your results in the appropriate folder structure as shown above.
4. Submit a pull request or contact the maintainers.

---

## Citation

If you use Mess in research, please cite:

@inproceedings{esmaili2024mess,
    title     = {A Mess of Memory System Benchmarking, Simulation and Application Profiling},
    author    = {Esmaili-Dokht, Pouya and Sgherzi, Francesco and Girelli, Valeria Soldera
                             and Boixaderas, Isaac and Carmin, Mariana and Monemi, Alireza
                             and Armejach, Adria and Mercadal, Estanislao and Llort, German
                             and Radojkovi{\'c}, Petar and Moreto, Miquel and Gim{\'e}nez, Judit
                             and Martorell, Xavier and Ayguad{\'e}, Eduard and Labarta, Jesus
                             and Confalonieri, Emanuele and Dubey, Rishabh and Adlard, Joshua},
    booktitle = {Proceedings of the 57th IEEE/ACM International Symposium on Microarchitecture (MICRO)},
    pages     = {136--152},
    year      = {2024},
    publisher = {IEEE}
}

---

## References

- [Mess Benchmark 2.0 (GitHub)](https://github.com/bsc-mem/Mess-2.0)
- [Mess Simulator](https://github.com/bsc-mem/Mess-Simulator)
- [Mess-Paraver](https://github.com/bsc-mem/Mess-Paraver)
- [Mess Paper (MICRO 2024)](https://ieeexplore.ieee.org/document/10345678)

---

<div align="center">
    <sub>Mess Framework is developed by the Memory Systems Team at the Barcelona Supercomputing Center (BSC).</sub>
</div>
