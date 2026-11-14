### Naeem Roussas

Systems and security researcher working on Linux kernel networking, threat intelligence, and public-infrastructure assurance.

I started as a Linux systems administrator at 16 (BGP/OSPF, Docker, PostgreSQL) and have spent four years since then splitting time between operational security work and independent research. In 2026 I shifted to independent security research full-time — publishing on election infrastructure assurance and kernel-boundary network security, building eBPF/XDP packet filters, and doing responsible-disclosure vulnerability research.

I finish my B.S. in Cybersecurity (SNHU, 3.95 GPA) in December 2026 and am applying to Computer Science Ph.D. programs for Fall 2027.

#### Research

- **Two accepted papers** at the Rice University EVT/WOTE Workshop (Dec 2026) on election infrastructure field assurance
- **IEEE Computer article** (Accepted) on game-related software supply-chain security — DOI: [10.1109/MC.2026.3730022](https://doi.org/10.1109/MC.2026.3730022)
- **IEEE TNSM submission** (Under Review) on eBPF kernel-boundary anomaly detection

#### Open-source prototypes

| Project | What it does | Stack |
|---|---|---|
| [QXDP](https://github.com/naeemjr/QXDP) | Sub-byte packet quantization for line-rate DDoS mitigation (21.9 Mpps, 0% FPR to 40% mutation) | eBPF/XDP · C · Go |
| [GhostNIC](https://github.com/naeemjr/GhostNIC) | eBPF detection research: passive packet observation and defensive audit at XDP/TC layers | eBPF · Go · C |
| [EdgeSight](https://github.com/naeemjr/EdgeSight) | Single-binary passive network detection with behavioral baselines and ATT&CK-mapped alerts | Go |
| [AEGIS-LOOP](https://github.com/naeemjr/AEGIS-LOOP) | LoRA/QLoRA fine-tuning pipeline for automated code review and vulnerability triage | Python · ML |
| [PolicyContinuity](https://github.com/naeemjr/PolicyContinuity) | Benchmark: do filesystem containment policies survive state changes? | Rust |
| [QUICScope](https://github.com/naeemjr/QUICScope) | Benchmark: when should a QUIC traffic monitor abstain instead of guess? | Rust |
