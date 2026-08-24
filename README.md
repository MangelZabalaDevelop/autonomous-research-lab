# Xpectra Research — Autonomous Research Lab

**AI-native vulnerability research, supervised by a human security expert and published for defenders.**

This repository is a public record of how autonomous AI agents perform deep, long-horizon security research. Each case reconstructs an already disclosed and vendor-remediated vulnerability inside an authorized laboratory, then documents its mechanics, evidence, detection opportunities, and defensive lessons.

The project is also a time capsule: as models and agent harnesses improve, future investigations will show how the research pipeline evolves.

## Research

- **Case 001:** [CVE-2026-73570 — Zimbra Collaboration Suite SNMP command injection](CVE-2026-73570/README.md)

> [!NOTE]
> Case 001 uses a controlled laboratory adaptation to exercise the vulnerable sink. It does not demonstrate that the same trigger path exists in an unmodified installation.

## AI-native methodology

The research, laboratory automation, exploitation artifacts, defensive content, documentation, editing, and media are produced by AI agents operating through controlled harnesses.

**Miguel Zabala**, Founder of [Xpectra.ai](https://xpectra.ai), acts as Human Research Supervisor: he defines objectives, contributes offensive-security judgment, requests clarifications, controls scope, and approves publication.

Case 001 was executed with agents powered by:

- **Qwen3.8-27B-FP8**
- **DeepSeek-V4-Flash-0731**

Prompts and private reasoning traces are not published.

## Research infrastructure

The local research environment consists of:

- one [Dell Pro Max Tower T2](https://www.dell.com/en-us/shop/desktop-computers/new-dell-pro-max-tower-t2-desktop/spd/dell-pro-max-fct2250-desktop/bts105d_fct2250_usx) with an [NVIDIA RTX PRO 6000 Blackwell Workstation Edition](https://www.nvidia.com/en-us/products/workstations/professional-desktop-gpus/rtx-pro-6000/);
- two [Dell Pro Max with GB10](https://www.dell.com/en-in/shop/desktop-computers/dell-pro-max-with-gb10/spd/dell-pro-max-fcm1253-micro) systems.

> Hardware provided by Dell Technologies through its Ambassador Program, powered by NVIDIA accelerated computing.

## Scope

- Only publicly disclosed vulnerabilities with an available vendor remediation are studied.
- Research is limited to owned or explicitly authorized systems.
- Offensive artifacts are published for analysis, detection, validation, and defense—not for active exploitation of third-party systems.
- Vendor binaries and licensed installation media are not redistributed.
- The original AI-generated case material is preserved as produced.

Original code and detection content are provided under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0). Original research prose and media are provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Third-party materials remain subject to their respective terms.

Contact: [m.zabala@xpectra.ai](mailto:m.zabala@xpectra.ai)
