# Debjyoti Mukherjee

**Turning compliance requirements into deployable evidence.**

Most GRC programs still treat compliance as a document problem — policies in SharePoint, evidence in email threads, access reviews in spreadsheets. I'm a GRC engineer treating that gap as an automation problem: Infrastructure as Code that encodes controls from day one, Policy as Code that fails closed in CI, evidence pipelines that produce timestamped artifacts auditors can actually sample, and cloud-native tooling that runs the reviews on a schedule instead of asking someone to remember.

The work clusters around three layers: a **lab layer** (hands-on CGE-P reference workspaces across AWS and GCP), an **assessment layer** (automated IAM access reviews and application risk scoring), and a **capstone layer** (wrapping deliberately non-compliant workloads in compliance-as-code until the pipeline passes).

## Featured

| Project | What it is |
|---------|------------|
| [**cgep-labs**](https://github.com/debjym/cgep-labs) | Hands-on labs and tested reference workspaces for the Certified GRC Engineer Practitioner (CGE-P). Terraform, Rego, Conftest, cosign, and OSCAL — one guide per lab, one deployable workspace per guide. Labs alternate AWS and GCP to make the compliance-by-default pattern cloud-agnostic. |
| [**AWS-Automated-Access-Review-Lab**](https://github.com/debjym/AWS-Automated-Access-Review-Lab) | Lab companion for zero-configuration IAM security assessment. Combines Security Hub, IAM Access Analyzer, and Bedrock-powered executive summaries into scheduled, email-delivered reports — built for SOC 2 Type 2 sampling and monthly access-review evidence. |
| [**aws_automated_access_review**](https://github.com/debjym/aws_automated_access_review) | Fork and extension of the AWS Access Review automation stack. Serverless IAM auditing with CSV findings, AI-generated narratives, and single-click CloudFormation deployment. |
| [**cgep-app-starter**](https://github.com/debjym/cgep-app-starter) | CGE-P Capstone Starter — Patient Intake API. Deliberately non-compliant. Fork, deploy, then govern. Every lab artifact drops directly into this repo; the capstone is assembly, not from-scratch construction. |
| [**App_R_Scorecard**](https://github.com/debjym/App_R_Scorecard) | Application risk scorecard — structured logic for rating application risk posture. A lightweight tool for translating qualitative risk factors into a repeatable score. |

## Community

**[GRC Engineering Club](https://grcengclub.com)** — Building the practitioner community for compliance-as-code. Contributing to [`GRCEngClub/cgep-labs`](https://github.com/GRCEngClub/cgep-labs) and the broader CGE-P certification path at [cert.grcengclub.com](https://cert.grcengclub.com).

## Credentials

| Certification / Training | Issuer |
|--------------------------|--------|
| Certified GRC Engineer - Practitioner *(in progress)* | GRC Engineering Club |
| <!-- Add your certifications here --> | |

**Selected training** — <!-- e.g. AWS Security Fundamentals | Mileva Security Labs -->

## Now / Next / Later

**Now**
- Working through the **CGE-P capstone** — assembling lab artifacts (Terraform modules, Rego policies, evidence pipeline, OSCAL exports) around the Patient Intake API until CI gates pass closed
- Extending **AWS Automated Access Review** — field-testing scheduled IAM reports as audit evidence for access-review controls

**Next**
- Harden **App_R_Scorecard** — codify application risk tiers with explicit control mappings (NIST 800-53 / SOC 2 CC series)
- Contribute lab clarity fixes and cloud version drift updates back to **cgep-labs**
- Explore **Agentic-AI** patterns for evidence-grounded GRC workflows — agents that can only assert what they retrieved

**Later**
- End-to-end capstone demo — non-compliant deploy → policy gate failure → remediate → signed evidence vault → OSCAL assessment results
- Reusable access-review control package — monthly IAM report + retention + auditor sampling playbook
- Open-source GRC portfolio hub contributions aligned with the [GRC Portfolio initiative](https://github.com/ajy0127/grc_portfolio)

## Connect

- **GitHub:** [github.com/debjym](https://github.com/debjym)
- **LinkedIn:** <!-- linkedin.com/in/your-profile -->
- **Location:** <!-- Your city, state/country -->
