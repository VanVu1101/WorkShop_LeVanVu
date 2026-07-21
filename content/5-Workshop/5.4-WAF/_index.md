---
title: "WAF"
date: 2026-07-21
weight: 4
chapter: false
pre: " <b> 5.4 </b> "
---

#### Overview

This workshop page documents the implementation of AWS WAF for a CloudFront-enabled web application, including the creation of protection packs (web ACLs), rule set management, and monitoring setup.

#### Scope

- Implement AWS WAF Web ACL protection pack for the application.
- Configure managed and custom rule groups to block suspicious traffic.
- Attach the protection pack to CloudFront or other edge resources.
- Review rule order, traffic monitoring, and logging recommendations.

#### Summary

The WAF protection pack named `Nhom4-WebACL-Protection` was created successfully. It includes a mix of managed AWS rule sets and custom rules, covering IPv4/IPv6 allow/block controls, GeoRule, rate-based rules for GET/POST, and body size restrictions. The deployed protection pack is designed to improve security posture while allowing legitimate traffic.

#### Detailed results

- Protection pack name: `Nhom4-WebACL-Protection`
- ARN and ID created in AWS WAF
- Rule sets included: `AWS-AWSManagedRulesAntiDDoSRuleSet`, `AWS-AWSManagedRulesAmazonIpReputationList`, `AWS-AWSManagedRulesCommonRuleSet`, and others
- Status: `Running in Count mode` for evaluation, with additional rules in allow/block list

#### Next steps

1. Enable logging and sampled requests for incident review.
2. Tune rule priorities and custom rules after observed traffic.
3. Configure AI monetization and smart recommendations if available.
4. Validate protection pack attachment on the target CloudFront distribution.

![WAF protection pack overview](/images/waf1.jpg)
![WAF protection pack overview](/images/waf2.jpg)
