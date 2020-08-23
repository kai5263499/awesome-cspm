awesome-cspm [![Build Status](https://api.travis-ci.org/kai5263499/awesome-cspm.svg?branch=master)](https://travis-ci.org/kai5263499/awesome-cspm)

------------------------------------------------------------------------------------------

A collection of cloud security related resources

* [**Threat Hunting in the Cloud**](#cloud-threat-hunting)

* [**Attacks**](#attacks)

* [**Attacker tools**](#attacker-tools)

* [**Defenses**](#defenses)

* [**Defender tools**](#defender-tools)

* [**Vendors**](#vendors)

* [**Cloud provider resources**](#cloud-provider-resources)

------------------------------------------------------------------------------------------

## Threat Hunting in the Cloud

### [Finding Evil in AWS](https://expel.io/blog/finding-evil-in-aws/)
* Account of finding and expelling a cloud intruder
### [Gathering Bearer Tokens from Azure Services](https://blog.netspi.com/gathering-bearer-tokens-azure/)
* Pen tester repot on how to identify attackers based on bearer token usage patterns
### [How to Build Threat Hunting Capability in AWS](https://pages.awscloud.com/rs/112-TZM-766/images/How-to-Build-a-Threat-Hunting-Capability-in-AWS_Whitepaper.pdf)
### [Threat Hunting Capability in the AWS Cloud](https://www.secureworldexpo.com/industry-news/threat-hunting-capability-in-the-aws-cloud)
### [Cloud Adoption Engineering the Next Generation of Cloud Governance](https://cloudrumblings.io/cloud-adoption-engineering-the-next-generation-of-cloud-governance-21fb1a2eff60)
### [Mitre Attack Matrix for Cloud Security](https://attack.mitre.org/matrices/enterprise/cloud/)
### [Mitre Cloud Security Attack Use Cases](http://oval.mitre.org/adoption/usecasesguide.html#usecases)


## Attacks
### [AWS Cryptojacking Worm Spreads Through the Cloud](https://threatpost.com/aws-cryptojacking-worm-cloud/158427/)
### [An AWS Virtual Machine Is Infected With Mining Malware. There Could Be Others](https://www-coindesk-com.cdn.ampproject.org/v/s/www.coindesk.com/aws-mining-malware-cryptojacking-monero)
### [AWS IAM Assume Role Vulnerabilities Found in Many Top Vendors](https://www.praetorian.com/blog/aws-iam-assume-role-vulnerabilities)
### [Full Infrastructure Takeover Of VMWare Cloud Director CVE-2020-3956](https://citadelo.com/en/blog/full-infrastructure-takeover-of-vmware-cloud-director-CVE-2020-3956/)
### [AWS IAM exploitation](https://securityriskadvisors.com/blog/aws-iam-exploitation/)
### [Wired Capital One Case Study](https://www.wired.com/story/capital-one-paige-thompson-case-hacking-spree/)
### [Krebs What We Can Learn From The Capital One Hack](https://krebsonsecurity.com/2019/08/what-we-can-learn-from-the-capital-one-hack/)
### [How online 'cloud buckets' are exposing private photos and other sensitive data](https://outline.com/Ke47MA)
### [Wyze Case Study of Leaked Customer Data](https://arstechnica.com/tech-policy/2019/12/surveillance-camera-company-wyze-confirms-leak-of-user-data/)
### [Case Study on How an Amazon Engineer Exposed Customer Credentials](https://www.upguard.com/breaches/identity-and-access-misstep-how-an-amazon-engineer-exposed-credentials-and-more)
### [VPN Traffic Mirroring in AWS](https://rhinosecuritylabs.com/aws/abusing-vpc-traffic-mirroring-in-aws/)
### [Plundering GCP Escelating Privledges in Google Cloud Platform (GCP)](https://about.gitlab.com/blog/2020/02/12/plundering-gcp-escalating-privileges-in-google-cloud-platform/)
### [Rhino Security Research Paper on S3 Ransomware Prevention and Defense](https://rhinosecuritylabs.com/aws/s3-ransomware-part-2-prevention-and-defense/)
### [Case Study on AWS Cloud RootKit](https://www.cbronline.com/news/aws-servers-hacked-rootkit-in-the-cloud)
### [Google Cloud Shell Root Compromise](https://threatpost.com/100k-google-cloud-shell-root-compromise/153665/)
### [Hunting Azure Admins for Vertical Escelation](https://www.lares.com/blog/hunting-azure-admins-for-vertical-escalation/)
### [How Attackers Could Use Azure Apps to Sneak into Microsoft 365](https://www.darkreading.com/cloud/how-attackers-could-use-azure-apps-to-sneak-into-office-365/d/d-id/1337399)

## Attacker tools

## [MicroBurst](https://github.com/Netspi/Microburst)
* PowerShell toolkit for attacking Azure
### [Capital One Cloud Breach Cloud Goat](https://rhinosecuritylabs.com/aws/capital-one-cloud_breach_s3-cloudgoat/)
* Terraform script to setup your own compromised cloud cyber range
### [Cloud Goat](https://github.com/RhinoSecurityLabs/cloudgoat)
* Terraform framework for creating compromised cloud environments
### [nimbostratus](http://andresriancho.github.io/nimbostratus/)
### [sadcloud](https://github.com/nccgroup/sadcloud)
* [sadcloud reports](https://ramimac.github.io/sadcloud-reports/)
### [Blackhat Briefing on Account Jumping and Post Infection Persistency and Lateral Movement in AWS](https://www.blackhat.com/docs/us-16/materials/us-16-Amiga-Account-Jumping-Post-Infection-Persistency-And-Lateral-Movement-In-AWS-wp.pdf)
### [Barq](https://github.com/Voulnet/barq)
### [Pacu](https://github.com/RhinoSecurityLabs/pacu)
### [SharpCloud](https://github.com/chrismaddalena/SharpCloud)

## Defenses

### [Getting started with IMSDv2](https://blog.appsecco.com/getting-started-with-version-2-of-aws-ec2-instance-metadata-service-imdsv2-2ad03a1f3650)
### [Netflix: Detecting Credential Compromise in AWS](https://netflixtechblog.com/netflix-cloud-security-detecting-credential-compromise-in-aws-9493d6fd373a)
### [Netflix: Preventing Credential Compromise in AWS](netflix-information-security-preventing-credential-compromise-in-aws-41b112c15179)
### [Breaking Attacker Kill Chsins in AWS IAM roles](http://webcache.googleusercontent.com/search?q=cache:k8TxfDRC4QEJ:https://disruptops.com/breaking-attacker-kill-chains-in-aws-iam-roles/&hl=en&gl=us&strip=1&vwsrc=0)
* [Origional on a flakey server](https://disruptops.com/breaking-attacker-kill-chains-in-aws-iam-roles/)
### [Azure Lighthouse](https://jussiroine.com/2019/07/azure-lighthouse-managing-customer-azure-tenants-as-a-service-provider/)
* Service from Microsoft for managing multiple Tenants and Subscriptions through delegated access
### [Breach Path Prediction: Getting Ahead of Cloud Breaches](https://www.accurics.com/blog/security/getting-ahead-of-cloud-breaches/)

## Defender tools

### [Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)
* Origionally built by a team at Capital One

## Vendors

### [HashiCorp Sentinel](https://www.hashicorp.com/sentinel/)
* [Compliance as code](https://www.hashicorp.com/resources/introduction-sentinel-compliance-policy-as-code/)
### [Google Beyond Prod](https://cloud.google.com/security/beyondprod/)
### [Broadcom CSPM](https://www.broadcom.com/products/cyber-security/endpoint/hybrid-cloud/cloud-workload-protection)
### [RedLock/PaloAlto](https://login.paloaltonetworks.com/?resume=/idp/DLKy1/resumeSAML20/idp/SSO.ping&spentity=RedLockSP)
### [Cloudsploit](https://console.cloudsploit.com/signin)

## Cloud provider resources

### [Cloud Services Resource Terminology - AWS vs. GCP vs. Azure](https://www.cloudhealthtech.com/blog/cloud-comparison-guide-glossary-aws-azure-gcp)
### [Cloud Platform Security and Monitoring](https://dsimg.ubm-us.net/envelope/400093/570523/ReliaQuest-WhitePaper-CloudPlatformSecurityAndMonitoring.pdf)
### [Azure security best practices and patterns](https://docs.microsoft.com/en-us/azure/security/fundamentals/best-practices-and-patterns)
### [Azure Security Logging and Auditing](https://docs.microsoft.com/en-us/azure/security/fundamentals/log-audit)
### [GCP Cloud Audit Logs](https://cloud.google.com/logging/docs/audit/)
### [Google Services with Audit Logs](https://cloud.google.com/logging/docs/audit/services)