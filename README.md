[![N|Solid](http://securityinside.info/wp-content/uploads/logo.png)](https://securityinside.info)

# CyberCamp18

Repository with the materials used on my CyberCamp masterclass named "AWS Cloud Security - Máxima seguridad en la nube de Amazon".

### Folder structure

```sh
CiberCamp18:
│   AWS_Security.pptx			// Main presentation
│   README.md			        // README file
│
├───cloudformation
│       aws-guarduty.yaml		// CF template to launch GuardDuty demo.
│       aws-vpc.template		// CF template to launch VPC demo.
│       aws-waf.template		// CF template to launch WAF demo.
│
├───kibana
│       GuardDutyFindings.json		// Template to create Kibana dashboard to show GuardDuty findings.
│
├───varios
│       status_report_sample.xlsx	// Sample of findings listed on an IAM status report.
│
└───videos
        AWS_certificate_manager.mov	// Demo with the how-to create a new certificate.
        AWS_create_account.mov		// Demo with the how-to create a new AWS account.
        IAM_federation.mov		// Demo with an aws access using a federated account.
```
