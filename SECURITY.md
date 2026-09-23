# Security Policy

## Supported Versions

Currently, only the latest version of the `react-embedded-sandbox` is supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

We take the security of this execution environment very seriously. If you discover a vulnerability, we would like to know about it so we can take steps to address it as quickly as possible.

Please do not report security vulnerabilities through public GitHub issues.

Instead, please email the maintainer or send a direct message through the contact methods listed in the README. You should receive a response within 48 hours.

## Active Threat Modeling

Because this project is a front-end execution sandbox that processes arbitrary user code (HTML/CSS/JS), it is inherently exposed to numerous attack vectors.

We are actively threat-modeling the application for:
- Code-injection vulnerabilities (XSS)
- Sandbox escapes from the iframe environment
- Malicious payload executions that could leak local storage or freeze the host browser

We are currently exploring integrations with advanced security scanning tools, including Codex Security, to automate vulnerability detection, model attack paths, and validate suspected vulnerabilities during the CI/CD pipeline.
