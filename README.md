# Awesome-Vendor-Security-Risk-Assessment-Engines

# Top Vendor Security Risk Assessment Engines Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Third-Party Risk Management, Security Questionnaires & Supply Chain Auditing*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Vendor Security Risk Assessment Engines**. These tools help organizations evaluate the security posture of their vendors, suppliers, and partners — automating questionnaire workflows, scoring risk, tracking compliance certifications, and auditing software supply chains.

**Examples** include UpGuard, Whistic, Prevalent, Panorays, SecurityScorecard, BitSight, ProcessUnity, Venminder, RiskRecon, and OneTrust Third-Party Risk (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, automated questionnaire scoring, and transparent supply chain analysis — ideal for security teams prioritizing data sovereignty, developers building TPRM platforms, and organizations avoiding per-vendor pricing.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[UpGuard](https://www.upguard.com/)**  
  Third-party risk and attack surface management platform with continuous vendor monitoring, security ratings based on 330+ external checks, and automated questionnaire workflows. Provides vendor risk reports covering website security, email security, phishing/malware, brand/reputation, and network security [citation:17].

- **[Whistic](https://www.whistic.com/)**  
  Vendor security assessment platform with AI-powered Vendor Summary that analyzes vendor-provided documentation (SOC 2 reports, security policies) to answer security control questions without waiting for questionnaire responses. Features confidence scoring, source citations, and automatic gap questionnaire generation [citation:2][citation:7][citation:12].

- **[Prevalent](https://www.prevalent.net/)**  
  Third-party risk management platform with automated vendor assessments, continuous monitoring, and remediation workflows.

- **[Panorays](https://panorays.com/)**  
  Third-party security posture management with automated vendor assessments and continuous monitoring.

- **[SecurityScorecard](https://securityscorecard.com/)**  
  Security ratings platform with continuous monitoring of vendor security posture across 10 risk factor groups.

- **[BitSight](https://www.bitsight.com/)**  
  Security ratings and third-party risk management platform with continuous monitoring and benchmarking.

- **[ProcessUnity](https://www.processunity.com/)**  
  Third-party risk management platform with vendor assessments, due diligence, and continuous monitoring.

- **[Venminder](https://www.venminder.com/)**  
  Third-party risk management platform with vendor due diligence and ongoing monitoring.

- **[RiskRecon](https://www.riskrecon.com/)**  
  Third-party cyber risk management platform with security ratings and vendor risk assessment.

- **[OneTrust Third-Party Risk](https://www.onetrust.com/)**  
  Third-party risk management within OneTrust platform with vendor assessments, continuous monitoring, and integration with privacy and GRC workflows.

## Open-Source GitHub Projects

- **[Probo](https://github.com/getprobo/probo)**  
  Open-source, self-hostable Governance, Risk, and Compliance (GRC) platform covering the full lifecycle: risk identification, control tracking, **vendor risk management**, data privacy (DPIA/TIA), access reviews, and audit programs. Features **270+ MCP tools** for AI agent integration, web console, `prb` CLI with 44+ command groups, GraphQL API, and n8n community node for no-code automation. Vendor risk capabilities include vendor inventory, automated website risk assessment, DPA/BAA tracking, and subprocessor discovery. ISC licensed [citation:3].

- **[Unicis Platform CE](https://github.com/UnicisTech/unicis-platform-ce)**  
  Open-source GRC platform positioned as a Vanta/Drata alternative with vendor risk management capabilities. Features standards and frameworks mapping (ISO 27001, GDPR, SOC 2, NIST), Statement of Applicability (SoA) export, REST API with OpenAPI 3.0 spec, audit logs, and role-based access control. Roadmap includes AI Questionnaire Automation and Continuous Control Monitoring [citation:13].

- **[vendorvet](https://github.com/cognis-digital/vendorvet)**  
  Open-source, self-hostable vendor risk assessment tool that scores security questionnaires and cross-references SBOMs against vulnerability advisories. Features **offline match against a bundled 262K-record OSV/GHSA vulnerability database** — zero network, air-gap ready. Combined vendor verdict from questionnaire + SBOM, output as table/JSON/SARIF 2.1.0, CI-friendly exit codes for procurement gates. Available as MCP server for AI agent integration. Ports in Python, JavaScript, Go, Rust, and Shell [citation:8].

- **[XORCISM](https://github.com/xorcism/xorcism)**  
  Open-source, self-hosted cybersecurity platform integrating **Third-Party Risk Management (TPRM)** alongside asset management, vulnerability management, SBOM/software supply chain security, and compliance/GRC. Features 1,100+ security tool integrations and local AI assistant. Designed to centralize fragmented security data into unified risk decisions [citation:18].

- **[OpenSSF Scorecard](https://github.com/ossf/scorecard)**  
  Automated security health metrics for open source projects. Scores repositories against supply chain security best practices including **Branch-Protection, Code-Review, Maintained, Dangerous-Workflow, Token-Permissions, Pinned-Dependencies, Vulnerabilities, Signed-Releases, SAST, and Fuzzing**. Each check returns 0-10 score with weighted aggregate. Essential for auditing third-party software supply chains automatically. JSON output for CI/CD gating [citation:5][citation:10][citation:15].

- **[ScanCode Toolkit](https://github.com/aboutcode-org/scancode-toolkit)**  
  Detects licenses, copyrights, and dependencies by scanning code to discover and inventory open source and third-party packages. Generates license and origin information for software composition analysis and compliance auditing. Sponsored by NLnet, Google Summer of Code, and nexB [citation:19].

- **[OSS Review Toolkit (ORT)](https://github.com/oss-review-toolkit/ort)**  
  A suite of tools to automate software compliance checks. Supports license identification, vulnerability detection, and policy evaluation across dependency manifests and lock files. Suitable for auditing vendor software supply chains at scale [citation:19].

- **[Chainloop](https://github.com/chainloop-dev/chainloop)**  
  Evidence store and policy engine for software supply chain attestations, SBOMs, VEX, SARIF, and QA reports. Enables automated compliance verification of vendor software artifacts [citation:19].

- **[Tern](https://github.com/tern-tools/tern)**  
  Software composition analysis tool and Python library that generates Software Bill of Materials (SBOM) for container images and Dockerfiles. Provides layer-by-layer view of container contents in human-readable, JSON, HTML, and SPDX formats [citation:19].

- **[Macaron](https://github.com/oracle/macaron)**  
  Extensible supply-chain security analysis framework from Oracle Labs supporting a wide range of build systems and CI/CD services. Can prevent supply chain attacks, detect malicious Python packages, and check conformance to frameworks like SLSA [citation:14].

- **[sbomqs](https://github.com/interlynk-io/sbomqs)**  
  SBOM quality scoring tool. Evaluates Software Bill of Materials against quality metrics for vendor artifact verification [citation:14].

- **[safedep/vet](https://github.com/safedep/vet)**  
  Tool for policy-driven vetting of open source dependencies. Enables automated risk assessment of vendor software components [citation:14].

### Additional Strong Open-Source Options

- **[OpossumUI](https://github.com/opossum-tool/OpossumUI)** — Lightweight app to audit and inventory large codebases for open source license compliance [citation:19].
- **[DeltaCode](https://github.com/aboutcode-org/deltacode)** — Compare two codebase scans (from ScanCode) to detect significant changes in dependencies and licenses [citation:19].
- **[Minefield](https://github.com/bitbomdev/minefield)** — Graphing SBOMs fast for visualizing software supply chain relationships [citation:14].
- **Dependency-Track** — Open-source SBOM analysis platform for continuous vulnerability monitoring of vendor components.
- **Grype** — Vulnerability scanner for container images and filesystems, useful for vendor artifact verification.

**Frameworks for building custom systems**: Combine **Probo** for full GRC and vendor risk lifecycle, **vendorvet** for questionnaire scoring and SBOM cross-referencing, **OpenSSF Scorecard** for automated supply chain health checks, **ScanCode** or **ORT** for license and dependency auditing, and **Dependency-Track** for continuous vulnerability monitoring to build a complete self-hosted vendor security risk assessment stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Vendor security risk assessment tools must comply with data protection regulations (GDPR, CCPA), industry standards (SOC 2, ISO 27001, NIST CSF), and contractual obligations.
- Self-hosted open-source solutions require proper security hardening, vulnerability database updates, and ongoing maintenance.

---

**Made for security teams, third-party risk managers, procurement officers, and developers building vendor risk assessment platforms.**  
Let's make vendor security risk assessment more open, automated, and supply-chain aware.
