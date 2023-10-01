---
layout: default
title: Security
nav_order: 5
---

# Security Process and Policy

This document provides the details on the security policy and details the processes
surrounding security handling including a how to guide on reporting a security vulnerability
for anything within the organization.

## Report A Vulnerability

We’re extremely grateful for security researchers and users who report vulnerabilities
to the community. All reports are thoroughly investigated by a set of maintainers.

To make a report please email the private security list at krv-security@sizek.cz
with the details.

### When To Send A Report

You think you have found a vulnerability in a krv project or a dependency of a [krv project](https://github.com/sizek/krv).


### Security Vulnerability Response

Each report will be reviewed and receipt acknowledged within 5 business days. This will set off the security review process detailed below.

Any vulnerability information shared with the security team stays within the krv project and will not be shared with others unless it is necessary to fix the issue. Information is shared only on a need to know basis.

We ask that vulnerability reporter(s) act in good faith by not disclosing the issue to others. And we strive to act in good faith by acting swiftly, and by justly crediting the vulnerability reporter(s) in writing.

As the security issue moves through triage, identification, and release the reporter of the security vulnerability will be notified. Additional questions about the vulnerability may also be asked of the reporter.

### Public Disclosure

A public disclosure of security vulnerabilities is released alongside release updates or details that fix the vulnerability. We try to fully disclose vulnerabilities once a mitigation strategy is available. Our goal is to perform a release and public disclosure quickly and in a timetable that works well for users. For example, a release may be ready on a Friday but for the sake of users may be delayed to a Monday.

CVEs will be assigned to vulnerabilities. Due to the process and time it takes to obtain a CVE ID, disclosures will happen first. Once the disclosure is public the process will begin to obtain a CVE ID. Once the ID has been assigned the disclosure will be updated.

If the vulnerability reporter would like their name and details shared as part of the disclosure process we are happy to. We will ask permission and for the way the reporter would like to be identified. We appreciate vulnerability reports and would like to credit reporters if they would like the credit.

## Security Team Membership

The security team is made up of a subset of the krv project maintainers who are willing and able to respond to vulnerability reports.

### Responsibilities

* Members SHOULD engage in each reported vulnerability, at a minimum to make sure it is being handled
* Members MUST keep the vulnerability details private and only share on a need to know basis

### Membership

New members are required to be active maintainers of krv project who are willing to perform the responsibilities outlined above. The security team is a subset of the maintainers. Members can step down at any time and may join at any time.

From time to time, krv project are deprecated. If at any time a security team member is found to be no longer be an active maintainer on active krv project, this individual will be removed from the security team.

## Patch and Release Team

When a vulnerability comes in and is acknowledged, a team - including maintainers of the krv project affected - will assembled to patch the vulnerability, release an update, and publish the vulnerability disclosure. This may expand beyond the security team as needed but will stay within the pool of krv project maintainers.

## Disclosures

Vulnerability disclosures are published as in documentation on the [krv homepafe](https://krv.sizek.cz/). The disclosures will contain an overview, details about the vulnerability, a fix for the vulnerability that will typically be an update, and optionally a workaround if one is available.

Disclosures will be published on the same day as a release fixing the vulnerability after the release is published.
