# Security Compliance Automation Framework

## Project Overview
Automated security compliance framework using Ansible and OpenSCAP for policy enforcement.

**Timeline**: January 2015 - October 2015  
**Technology Stack**: Python 2.7, Ansible, OpenSCAP, Jenkins, MySQL  
**Role**: IT Administrator - Etech Eritrea PLC

## Features
- Automated SCAP security scanning
- Ansible-based remediation playbooks
- Policy engine for compliance rules
- Jenkins CI/CD integration
- Comprehensive audit logging
- REST API for integrations
- Role-based access control (RBAC)
- Compliance trend analysis
- Automated notifications

## Architecture
- **OpenSCAP Scanner**: Security assessment engine
- **Ansible Automation**: Configuration management
- **Policy Engine**: Compliance rule processing
- **Jenkins Pipeline**: Automated workflows
- **MySQL Database**: Audit and compliance data
- **REST API**: External system integration

## Setup
```bash
# Install dependencies
sudo yum install ansible openscap-scanner
pip install -r requirements.txt

# Configure compliance policies
ansible-playbook playbooks/setup-compliance.yml

# Start Jenkins pipeline
java -jar jenkins.war --httpPort=8080
```