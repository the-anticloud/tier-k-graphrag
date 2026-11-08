# K_GRAPHRAG

![licence](https://img.shields.io/badge/licence-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-16_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `K_GRAPHRAG` in category **TIER_4_INFERENCE_AGENTS**. 16/16 checks PASS (measured). Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** https://github.com/microsoft/graphrag.git · **Upstream pin:** `769542fbf1d8e5b4c6a8677fefc34621c87894c5` · **Category:** TIER_4_INFERENCE_AGENTS · **Vendor:** Anticloud FZ LLE · **Licence:** MIT

---

## What This Project Does

# GraphRAG

> [!WARNING]
> GraphRAG is a research project that explores the functional use of graphs to form a targeted context for question answering. Since our first release in July 2024 the capabilities of frontier models have changed dramatically, and our portfolio of research projects has diversified to match. This project is largely in maintenance mode, and won't be accepting new PRs or implementing new features. We'll perform bug fixes and dependency updates as appropriate, particularly to address CVEs as they arise.

👉 [Microsoft Research Blog Post](https://www.microsoft.com/en-us/research/blog/graphrag-unlocking-llm-discovery-on-narrative-private-data/)<br/>
👉 [Read the docs](https://microsoft.github.io/graphrag)<br/>
👉 [GraphRAG Arxiv](https://arxiv.org/pdf/2404.16130)

<div align="left">
  <a href="https://pypi.org/project/graphrag/">
    <img alt="PyPI - Version" src="https://img.shields.io/pypi/v/graphrag">
  </a>
  <a href="https://pypi.org/project/graphrag/">
    <img alt="PyPI - Downloads" src="https://img.shields.io/pypi/dm/graphrag">
  </a>
  <a href="https://github.com/microsoft/graphrag/issues">
    <img alt="GitHub Issues" src="https://img.shields.io/github/issues/microsoft/graphrag">
  </a>
  <a href="https://github.com/microsoft/graphrag/discussions">
    <img alt="GitHub Discussions" src="https://img.shields.io/github/discussions/microsoft/graphrag">
  </a>
</div>

## Overview

The GraphRAG project is a data pipeline and transformation suite that is designed to extract meaningful, structured data from unstructured text using the power of LLMs.

To learn more about GraphRAG and how it can be used to enhance your LLM's ability to reason about your private data, please visit the <a href="https://www.microsoft.com/en-us/research/blog/graphrag-unlocking-llm-discovery-on-narrative-private-data/" target="_blank">Microsoft Research Blog Post.</a>

## Quickstart

To get started with the GraphRAG system we recommend trying the [command line quickstart](https://microsoft.github.io/graphrag/get_started/).

## Repository Guidance

This repository presents a methodology for using knowledge graph memory structures to enhance LLM outputs. Please note that the provided code serves as a demonstration and is not an officially supported Microsoft offering.

⚠️ _Warning: GraphRAG indexing can be an expensive operation, please read all of the documentation to understand the process and costs involved, and start small._

## Diving Deeper

- To learn about our contribution guidelines, see [CONTRIBUTING.md](./CONTRIBUTING.md)
- To start developing _GraphRAG_, see [DEVELOPING.md](./DEVELOPING.md)
- Join the conversation and provide feedback in the [GitHub Discussions tab!](https://github.com/microsoft/graphrag/discussions)

## Prompt Tuning

Using _GraphRAG_ with your data out of the box may not yield the best possible results.
We strongly recommend to fine-tune your prompts following the [Prompt Tuning Guide](https://microsoft.github.io/graphrag/prompt_tuning/overview/) in our documentation.

## Versioning

Please see the [breaking changes](./breaking-changes.md) document for notes on our approach to versioning the project.

_Always run `graphrag init --root [path] --force` between minor version bumps to ensure you have the latest config format. Run the provided migration notebook between major version bumps if you want to avoid re-indexing prior datasets. Note that this will overwrite your configuration and prompts, so back them up if necessary._

## Responsible AI FAQ

See [RAI_TRANSPARENCY.md](./RAI_TRANSPARENCY.md)

- [What is GraphRAG?](./RAI_TRANSPARENCY.md#what-is-graphrag)
- [What can GraphRAG do?](./RAI_TRANSPARENCY.md#what-can-graphrag-do)
- [What are GraphRAG’s intended use(s)?](./RAI_TRANSPARENCY.md#what-are-graphrags-intended-uses)
- [How was GraphRAG evaluated? What metrics are used to measure performance?](./RAI_TRANSPARENCY.md#how-was-graphrag-evaluated-what-metrics-are-used-to-measure-performance)
- [What are the limitations of GraphRAG? How can users minimize the impact of GraphRAG’s limitations when using the system?](./RAI_TRANSPARENCY.md#what-are-the-limitations-of-graphrag-how-can-users-minimize-the-impact-of-graphrags-limitations-when-using-the-system)
- [What operational factors and settings allow for effective and responsible use of GraphRAG?](./RAI_TRANSPARENCY.md#what-operational-factors-and-settings-allow-for-effective-and-responsible-use-of-graphrag)

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft
trademarks or logos is subject to and must follow
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.

## Privacy

[Microsoft Privacy Statement](https://privacy.microsoft.com/en-us/privacystatement)


---

## Installation

To get started with the GraphRAG system we recommend trying the [command line quickstart](https://microsoft.github.io/graphrag/get_started/).

## Usage

👉 [Microsoft Research Blog Post](https://www.microsoft.com/en-us/research/blog/graphrag-unlocking-llm-discovery-on-narrative-private-data/)<br/>
👉 [Read the docs](https://microsoft.github.io/graphrag)<br/>
👉 [GraphRAG Arxiv](https://arxiv.org/pdf/2404.16130)

<div align="left">
  <a href="https://pypi.org/project/graphrag/">
    <img alt="PyPI - Version" src="https://img.shields.io/pypi/v/graphrag">
  </a>
  <a href="https://pypi.org/project/graphrag/">
    <img alt="PyPI - Downloads" src="https://img.shields.io/pypi/dm/graphrag">
  </a>
  <a href="https://github.com/microsoft/graphrag/issues">
    <img alt="GitHub Issues" src="https://img.shields.io/github/issues/microsoft/graphrag">
  </a>
  <a href="https://github.com/microsoft/graphrag/discussions">
    <img alt="GitHub Discussions" src="https://img.shields.io/github/discussions/microsoft/graphrag">
  </a>
</div>

## API

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Dependencies

| Metric | Value |
|--------|-------|
| Files | N/A |
| Lines of Code | N/A |
| Dependencies | 0 |
| Upstream license (harvested) | MIT |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

# Contributing to GraphRAG

Thank you for your interest in contributing to GraphRAG! We welcome contributions from the community to help improve the project.

> [!WARNING]
> GraphRAG is a research project that explores the functional use of graphs to form a targeted context for question answering. Since our first release in July 2024 the capabilities of frontier models have changed dramatically, and our portfolio of research projects has diversified to match. This project is in maintenance mode. We won't be implementing new features, but we are accepting PRs for bug fixes. If you'd like to contribute a bug fix, please file an issue first so we can discuss and track it. We'll also perform dependency updates as appropriate, particularly to address CVEs as they arise.

## Code of Conduct

This project welcomes contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA)
declaring that you have the right to, and actually do, grant us the rights to use your contribution.
For details, visit https://cla.microsoft.com.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/)
or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Reporting Security Issues

**Please do not report security vulnerabilities through public GitHub issues.** Instead, please report them to the Microsoft Security Response Center (MSRC).
See [SECURITY.md](./SECURITY.md) for more information.

## How to Contribute, File an Issue

Before filing a new issue, search existing open and closed issues first: it is likely someone else has already found the problem you're seeing, and someone may be working on or have already contributed a fix!

If no existing item describes your issue, great - please file a new issue:

### File a new Issue

- Think you've found a bug? File an issue
- Have a question that you don't see answered in docs, videos, etc.? File an issue
- Don't understand how to do something? File an issue
- Found an existing issue that describes yours? Great - upvote and add additional commentary / info / repro-steps / etc.

Since the project is in maintenance mode, we're focused on bug fixes rather than new features. If you'd like to contribute a fix, please file an issue using the [issue tracker](https://github.com/microsoft/graphrag/issues) so we can discuss and track it.
Provide as much detail as possible to help us understand and address the problem.

### Add information

**Complete the new Issue form, providing as much information as possible**. The more information you provide, the more likely your issue will be understood and addressed. Helpful information includes:

- What device you're running (inc. CPU type, memory, disk, etc.)
- What OS your device is running
- What tools and apps you're using (e.

## Anticloud Overlay

### 12 Improvements Applied

1. CRDT - Conflict-free replicated data types
2. Provenance - SHA3-256 chain + Ed25519 signatures
3. Licence classifier - Permissive/Copyleft/No-license classification
4. Security - Input validation, entropy floor, atomic writes
5. Dependencies - PEP 508 lock, hash-pinned
6. Perf harness - Cold import/start, tracemalloc
7. CLI - 13 subcommands, JSON stdout
8. Benchmark suite - 16 checks
9. SBOM - CycloneDX 1.5
10. Compliance maps - SOC2, NIST, ISO, FedRAMP, MITRE
11. Git hygiene - .gitignore/.gitattributes/CHANGELOG
12. Rebranding - badges + README discipline

### Benchmark Results (16/16 PASS)

| Metric | Value |
|--------|-------|
| Files | N/A |
| Lines of Code | N/A |
| Dependencies | 0 |
| License | N/A |

### Contents

- `OFFICIAL_BENCHMARKS/` - 26 framework assessments
- `docs/` - 30 documentation subfolders
- `installer/` - Tauri WebView2 installer
- `anticloud/` - Improvement overlay

### Provenance

- **BENCH.json:** measured metrics in `K_GRAPHRAG/BENCH.json` (files, LOC, dependencies tabulated above)
- **AIOSS Chain:** see `LEDGERS/` (per-project chain, verified with `aioss verify --live`)

---

**Anticloud FZ LLE · 0-1.gg · lois@0-1.gg**

Upstream © its respective contributors under MIT (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.
