# Hands-on-DevSecOps-Supply-Chain-IaC-Security-CTF-Labs-SecByte-Index
A curated index of hands-on DevSecOps CTF labs focusing on CI/CD pipeline security, GitHub &amp; Azure DevOps hardening, SBOMs, supply chain protection, Infrastructure as Code (Terraform) security, and dependency scanning.
# DevSecOps, CI/CD Supply Chain & IaC Security CTF Lab Collection

Welcome to the **DevSecOps, CI/CD Supply Chain & IaC Security CTF Lab Collection**. This repository serves as a structured, searchable catalog of hands-on security labs hosted on Learn SecByte.

This index covers modern cloud-native security disciplines including CI/CD pipeline defense, Software Bill of Materials (SBOM) management, Git/GitHub secret detection, Azure DevOps hardening, Infrastructure as Code (IaC) security, and automated scanning.

---

## Lab Collection Index

### 1. CI/CD Pipeline & Supply Chain Security
* **Supply Chain Security: From Dependency Risk to Build Pipeline**  
  *Lab Link:* [https://learn.secbyte.org/ctf/supply-chain-security-from-dependency-risk-to-build-pipeline](https://learn.secbyte.org/ctf/supply-chain-security-from-dependency-risk-to-build-pipeline)  
  *Focus:* Identifying third-party dependency risks, typosquatting, malicious packages, and securing build automation systems.

* **Pipeline Security: Securing CI/CD from Commit to Production**  
  *Lab Link:* [https://learn.secbyte.org/ctf/pipeline-security-securing-ci-cd-from-commit-to-production](https://learn.secbyte.org/ctf/pipeline-security-securing-ci-cd-from-commit-to-production)  
  *Focus:* Hardening build runners, enforcing code review policies, preventing arbitrary command injection in workflows, and securing artifact delivery.

* **CI/CD Security Lab: Pipeline Secrets & Supply Chain Defense**  
  *Lab Link:* [https://learn.secbyte.org/ctf/cicd-security-lab-pipeline-secrets-supply-chain-defense](https://learn.secbyte.org/ctf/cicd-security-lab-pipeline-secrets-supply-chain-defense)  
  *Focus:* Preventing pipeline secret leaks, unmasked environment variables, runner poisoning, and toxic combination vulnerabilities.

* **SBOM Fundamentals: From Inventory to Incident Response**  
  *Lab Link:* [https://learn.secbyte.org/ctf/sbom-fundamentals-from-inventory-to-incident-response](https://learn.secbyte.org/ctf/sbom-fundamentals-from-inventory-to-incident-response)  
  *Focus:* Generating, parsing, and managing Software Bill of Materials (SPDX/CycloneDX) to accelerate vulnerability response.

* **Artifact Security: Detect, Decode, Defend Hidden Digital Evidence**  
  *Lab Link:* [https://learn.secbyte.org/ctf/artifact-security-detect-decode-defend-hidden-digital-eviden](https://learn.secbyte.org/ctf/artifact-security-detect-decode-defend-hidden-digital-eviden)  
  *Focus:* Inspecting build artifacts, container images, compiled binaries, and metadata for hidden credentials and backdoors.

### 2. Version Control & SCM Hardening
* **Git Security: Secrets, History, Repository Hardening**  
  *Lab Link:* [https://learn.secbyte.org/ctf/git-security-secrets-history-repository-hardening](https://learn.secbyte.org/ctf/git-security-secrets-history-repository-hardening)  
  *Focus:* Scrubbing commit history, pre-commit hooks, preventing secret leaks, branch protection rules, and signed commits.

* **GitHub Security: Secret Sprawl & Supply Chain Defense**  
  *Lab Link:* [https://learn.secbyte.org/ctf/github-security-secret-sprawl-supply-chain-defense](https://learn.secbyte.org/ctf/github-security-secret-sprawl-supply-chain-defense)  
  *Focus:* Hardening GitHub Actions workflows, secret scanning, Dependabot alerts, OIDC identity trust, and preventing workflow injection.

* **Azure DevOps Security: Pipelines, Identity, Secrets**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-devops-security-pipelines-identity-secrets](https://learn.secbyte.org/ctf/azure-devops-security-pipelines-identity-secrets)  
  *Focus:* Securing Service Connections, variable groups, self-hosted agent pools, and permission boundaries inside Azure DevOps.

### 3. Infrastructure as Code (IaC) & Automated Scanning
* **Infrastructure as Code Security: From Misconfigurations to Compliance**  
  *Lab Link:* [https://learn.secbyte.org/ctf/infrastructure-as-code-security-from-misconfigurations-to-co](https://learn.secbyte.org/ctf/infrastructure-as-code-security-from-misconfigurations-to-co)  
  *Focus:* Auditing template security, enforcing policy-as-code (OPA/Conftest), shift-left scanning, and preventing cloud misconfigurations.

* **Terraform Security Fundamentals**  
  *Lab Link:* [https://learn.secbyte.org/ctf/terraform-security-fundamentals](https://learn.secbyte.org/ctf/terraform-security-fundamentals)  
  *Focus:* Securing state files, encryption at rest, managing sensitive variables, avoiding cleartext secrets, and module security.

* **Container Scanning: Fundamentals and Exploitation Paths**  
  *Lab Link:* [https://learn.secbyte.org/ctf/container-scanning-fundamentals-and-exploitation-paths](https://learn.secbyte.org/ctf/container-scanning-fundamentals-and-exploitation-paths)  
  *Focus:* Evaluating static container scanners (Trivy/Grype), identifying CVE false positives, base image analysis, and exploitability paths.

* **Dependency Scanning: From Vulnerable Libraries to Secure Builds**  
  *Lab Link:* [https://learn.secbyte.org/ctf/dependency-scanning-from-vulnerable-libraries-to-secure-buil](https://learn.secbyte.org/ctf/dependency-scanning-from-vulnerable-libraries-to-secure-buil)  
  *Focus:* Automated Software Composition Analysis (SCA), license compliance auditing, lockfile tampering, and remediation strategies.

---

## Learning Path

### Path A: Pipeline & Supply Chain Defender
1. **SCM Security:** Start with [Git Security](https://learn.secbyte.org/ctf/git-security-secrets-history-repository-hardening) and [GitHub Security](https://learn.secbyte.org/ctf/github-security-secret-sprawl-supply-chain-defense) or [Azure DevOps Security](https://learn.secbyte.org/ctf/azure-devops-security-pipelines-identity-secrets).
2. **CI/CD Hardening:** Secure workflows using [Pipeline Security](https://learn.secbyte.org/ctf/pipeline-security-securing-ci-cd-from-commit-to-production) and [CI/CD Security Lab](https://learn.secbyte.org/ctf/cicd-security-lab-pipeline-secrets-supply-chain-defense).
3. **Software Supply Chain:** Implement [Supply Chain Security](https://learn.secbyte.org/ctf/supply-chain-security-from-dependency-risk-to-build-pipeline), [SBOM Fundamentals](https://learn.secbyte.org/ctf/sbom-fundamentals-from-inventory-to-incident-response), and [Artifact Security](https://learn.secbyte.org/ctf/artifact-security-detect-decode-defend-hidden-digital-eviden).

### Path B: DevSecOps Automation & IaC Specialist
1. **Automated Scanning:** Master tools with [Dependency Scanning](https://learn.secbyte.org/ctf/dependency-scanning-from-vulnerable-libraries-to-secure-buil) and [Container Scanning](https://learn.secbyte.org/ctf/container-scanning-fundamentals-and-exploitation-paths).
2. **IaC Hardening:** Secure cloud provisioning using [Infrastructure as Code Security](https://learn.secbyte.org/ctf/infrastructure-as-code-security-from-misconfigurations-to-co) and [Terraform Security Fundamentals](https://learn.secbyte.org/ctf/terraform-security-fundamentals).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding link to open the lab directly on Learn SecByte.
3. Read the scenario details, analyze the source code, CI/CD pipelines, or IaC templates, and fulfill the exercise requirements.
4. remediate misconfigurations, discover secrets, or exploit workflow vulnerabilities to capture flags.

---

## Target Audience

* **DevSecOps Engineers:** Shift security left by integrating SAST, SCA, secret detection, and IaC scanning into delivery pipelines.
* **Cloud & Platform Engineers:** Hardened Terraform codebases, state files, and SCM platform configurations.
* **Security Champions & Software Developers:** Learn secure coding practices, secret management, and supply chain risk mitigation.
* **Penetration Testers:** Understand CI/CD pipeline attack vectors, runner poisoning, and workflow command injection.

---

## Disclaimer

All lab links provided in this repository point to official interactive training environments on Learn SecByte. All activities and exercises must be conducted exclusively for educational, defensive, and authorized research purposes.
