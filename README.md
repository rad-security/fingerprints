# RAD Security Fingerprints

## Introduction
KSOC introduces the RAD security standard, a revolutionary approach to combat the rising threat of software supply chain attacks. Fueled by eBPF, this standard establishes verified cloud workload fingerprints, offering a robust defense against zero-day attacks.  This repository provides a free online catalog of verified fingerprints for cloud workloads, as well as SBOMs for analyzed images, and detected vulnerabilities for the packages enumerated in the SBOMs.

### What are RAD Security Fingerprints
Powered by eBPF, RAD security creates behavioral fingerprints of cloud workloads, providing a transparent defense against zero-day software supply chain attacks. These fingerprints, available in this free online catalog, enable DevSecOps teams to compare verified, clean runtime fingerprints with the actual image running in their environment.

# SBOMs
SBOMs, or software bill of materials, are a list of components that make up a software product.  SBOMs are a critical component of software supply chain security, as they provide a list of all components that make up a software product.  This allows DevSecOps teams to quickly identify and remediate vulnerabilities in their software supply chain.  This repository provides SBOMs for all images analyzed by the RAD security platform.  SBOMs are produced using [Syft](https://github.com/anchore/syft), an open source tool for generating SBOMs, and are available in the `sbom.json` file for each image.

# Vulnerabilities
The images analyzed by RAD Security are scanned for vulnerabilities using [Grype](https://github.com/anchore/grype),
and those vulnerabilities are listed in the `vulnerabilities.json` file for each image.


