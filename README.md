# Golang Vulnerability Check with Trivy

[![Run Vulnerability Check](https://github.com/gamertense/golang-trivy-scan/actions/workflows/trivy-scan.yml/badge.svg)](https://github.com/gamertense/golang-trivy-scan/actions/workflows/trivy-scan.yml)

This repository contains a GitHub Action that scans Golang dependencies for vulnerabilities using [Trivy](https://trivy.dev/). Detected vulnerabilities are listed in the Security tab of this repository.

## Features

- Automated scanning of Golang dependencies.
- Integration with GitHub Actions for continuous security checks.
- Detailed vulnerability reports accessible via the Security tab.

## Usage

To use this GitHub Action in your repository, follow these steps:

1. Create a `.github/workflows/trivy-scan.yml` file in your repository.
2. Copy the contents of the `trivy-scan.yml` file from this repository into your newly created file.
3. Commit and push the changes to your repository.

The action will automatically run and scan your Golang dependencies for vulnerabilities.
