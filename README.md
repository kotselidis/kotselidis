## Christos Kotselidis

Associate Professor (Reader) at **[The University of Manchester](https://www.manchester.ac.uk/)** ([Beehive Lab](https://github.com/beehive-lab)) and Co-founder at **[Beestream.ai](https://beestream.ai)**.

I lead the [TornadoVM](https://www.tornadovm.org) and [jitLLM](https://github.com/beehive-lab/jitllm) projects and am the technical coordinator of the Horizon Europe/UKRI [AERO project](https://aero-project.eu).
My work spans hardware and software: hw/sw co-designed CPUs and VMs, heterogeneous acceleration, compilers, virtual machines, and their intersection with AI.

[Website](https://kotselidis.net/) ·
[Google Scholar](https://scholar.google.co.uk/citations?user=A8z1ZuoAAAAJ&hl=en) ·
[ORCID](https://orcid.org/0000-0002-8146-3503) ·
[LinkedIn](https://www.linkedin.com/in/kotselidis) ·
[Bluesky](https://bsky.app/profile/kotselidis.net) ·
[Mastodon](https://mastodon.online/@kotselidis) ·
[Email](mailto:christos.kotselidis@manchester.ac.uk)

---

### TornadoVM

**[TornadoVM](https://github.com/beehive-lab/TornadoVM)**: *Write Java. Run on GPUs. Fast.*
A plug-in to OpenJDK and GraalVM that JIT-compiles Java to OpenCL, CUDA and HIP and runs it on GPUs and multi-core CPUs.

[![Stars](https://img.shields.io/github/stars/beehive-lab/TornadoVM?style=flat-square)](https://github.com/beehive-lab/TornadoVM/stargazers)
[![Release](https://img.shields.io/github/v/release/beehive-lab/TornadoVM?style=flat-square)](https://github.com/beehive-lab/TornadoVM/releases)

### Built on TornadoVM

| Project | What it does |
|---|---|
| [**jitLLM**](https://github.com/beehive-lab/jitllm) | LLM inference and serving for the JVM on GPUs |
| [**jitNN**](https://github.com/beestream-ai/jitNN) | Deep learning in Java: training and inference, fast and portable |
| [**jitCast**](https://github.com/beestream-ai/jitCast) | Time-series foundation models in Java |
| [**jitIceberg**](https://github.com/beestream-ai/jitIceberg) | Apache Iceberg scans, compaction and deletes on NVIDIA GPUs |
| [**spark-jitudf**](https://github.com/beestream-ai/spark-jitudf) | Compiles Spark UDFs that RAPIDS declines into GPU kernels |
| [**flink-jitsql**](https://github.com/beestream-ai/flink-jitsql) | Flink SQL operators offloaded to GPUs, no query changes |
| [**jitPaimon**](https://github.com/beestream-ai/jitPaimon) | Apache Paimon primary-key compaction on GPUs |

### Tooling and demos

- [TornadoInsight](https://github.com/beehive-lab/tornado-insight): TornadoVM in IntelliJ IDEA
- [tornadoviz](https://github.com/beehive-lab/tornadoviz): visualise TornadoVM execution logs
- [docker-tornadovm](https://github.com/beehive-lab/docker-tornadovm): Docker images for TornadoVM on GPUs
- [kfusion-tornadovm](https://github.com/beehive-lab/kfusion-tornadovm) and [TornadoVM Ray Tracer](https://github.com/beehive-lab/TornadoVM-Ray-Tracer): real-time graphics in Java
- [TornadoVM vs CUDA (Devoxx 2026)](https://github.com/beehive-lab/tornadovm-devoxx2026-cuda-demos): Java vs hand-written CUDA, explained with Nsight Compute
- [Hands-on lab](https://github.com/beehive-lab/tornadovm-hands-on-lab) and [talks and slides](https://github.com/beehive-lab/tornadovm-presentations)

### Book

[*Programming Heterogeneous Hardware via Managed Runtime Systems*](https://link.springer.com/book/10.1007/978-3-031-49559-5) (Springer)

### Recent talks

- TornadoVM at Voxxed Days CERN 2026: [video](https://youtu.be/WNQ5ylMs4Ok)
- TornadoVM at Devoxx Belgium 2025: [video](https://www.youtube.com/watch?v=oRVtTEbtt_Y)
- GPULlama3.java at Devoxx Belgium 2025: [video](https://youtu.be/PO6wOtzUb3w)

More on [publications](https://kotselidis.net/publications/) and [projects](https://kotselidis.net/projects/).
