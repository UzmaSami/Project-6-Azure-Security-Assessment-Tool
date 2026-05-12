
# 🔐 Azure Security Assessment Tool

## Overview
Automated PowerShell tool that assesses Azure
environment security across 24+ controls in
6 categories and generates a beautiful
interactive HTML report with remediation guidance.

*Author:* Uzma Sami | AZ-104 | AZ-500
*Language:* Pure PowerShell
*Cost:* £0 — No Azure resources consumed

## Architecture
![Architecture](docs/architecture-diagram.png)

# Report Features

- Overall security score with grade (A-F)
- Color coded findings (Critical/High/Medium/Low)
- Interactive filter buttons (All/Failed/Warnings/Passed)
- Detailed remediation guidance per finding
- CSV export for further analysis
- HTML report

## Prerequisites

- PowerShell 7.x
- Az PowerShell Module
- Microsoft Graph
- Azure Reader access minimum
