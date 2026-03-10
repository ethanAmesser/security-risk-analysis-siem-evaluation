# Security Risk Analysis & SIEM Evaluation

## Overview
Performed a security risk analysis of the UBNetDef Wiki infrastructure to determine whether sensitive personally identifiable information (SPII) was present and to evaluate the need for enterprise SIEM deployment.

## Key Analysis Areas
- PII risk assessment of MediaWiki user data
- Threat likelihood and impact evaluation
- Security monitoring requirements analysis
- SIEM platform comparison (SolarWinds vs Wazuh)

## Findings
- The system stores only usernames, hashed passwords, and optional email/real name fields
- No sensitive PII exists within the database schema
- Regulatory risk exposure is low compared to systems storing financial or government identifiers

## Security Recommendation
Recommended deploying **Wazuh SIEM** as a cost-effective monitoring solution providing:

- centralized log management
- file integrity monitoring
- intrusion detection
- security configuration assessment

## Skills Demonstrated
- Security risk analysis
- SIEM architecture evaluation
- PII classification and compliance analysis
- security monitoring strategy
- threat likelihood assessment

## Full Report
📄 [View Full Risk Analysis Report](security-risk-analysis-siem-evaluation.pdf)
