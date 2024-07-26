# GitLab Releases Security Advisory - 20240726003

## Overview

GitLab, the widely used code collaboration platform addresses vulnerabilities across multiple versions of its software. While none of the flaws are classified as "critical," at the time of writing one high-severity cross-site scripting (XSS) bug could have serious consequences if not patched promptly.

## What is vulnerable?

| Product(s) Affected | Version(s) | CVE | CVSS | Severity | 
| --- | --- | --- | --- | --- | 
| Enterprise Edition (EE) | - 16.11 **before** 17.0.5 <br/> - 17.1 **before** 17.1.3 <br/> - 17.2 **before** 17.2.1 | [CVE-2024-5067](https://nvd.nist.gov/vuln/detail/CVE-2024-5067) | 4.4  | Medium | 
| Community Edition (CE) and Enterprise Edition (EE) | - 16.7 **before** 17.0.5 <br/> - 17.1 **before** 17.1.3 <br/> - 17.2 **before** 17.2.1 | [CVE-2024-7057](https://nvd.nist.gov/vuln/detail/CVE-2024-7057) | 4.3  | Medium | 
| Community Edition (CE) and Enterprise Edition (EE) | - 12.0 **before** 17.0.5 </br> - 17.1 **before** 17.1.3 </br> - 17.2 **before** 17.2.1 | [CVE-2024-0231](https://nvd.nist.gov/vuln/detail/CVE-2024-0231) | 2.7 | Low | 

## What has been observed?

There is no evidence of exploitation affecting Western Australian Government networks at the time of publishing.

## Recommendation

The WA SOC recommends administrators apply the solutions as per vendor instructions to all affected devices within expected timeframe of *one month...* (refer [Patch Management](../guidelines/patch-management.md)):

- GitLab Patch Release: <https://about.gitlab.com/releases/2024/07/24/patch-release-gitlab-17-2-1-released/>

## Additional References

- SecurityOnline blog post: <https://securityonline.info/gitlab-patches-six-security-flaws-urges-immediate-update/>
