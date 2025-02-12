# **CSCL1030 CloudOps Tools and Techniques - Lab 2**

**Name:** Vishal Bichkunde  
**Student ID:** 220969614

## **Objective**
This lab focuses on cloud automation using AWS and Ansible. The main goal is to configure a control node, provision managed nodes, set up Ansible configurations, and deploy applications seamlessly.

## **Implementation Steps**

### **1. Control Node Setup**
- Configured SSH access for the control node.
- Added the SSH key to `id_rsa.pub` for authentication.

### **2. Managed Node Provisioning**
- Launched four AWS-managed nodes to act as deployment targets.
- Established secure connections between nodes.

### **3. Ansible Configuration**
- Created and updated the `hosts.ini` inventory file.
- Modified Ansible’s `.cfg` configuration for execution settings.

### **4. Automation Execution**
- Ran Ansible playbooks to apply configurations to managed nodes.
- Verified successful automation with test cases.

### **5. Application Deployment**
- Created an Ansible playbook (`install_cloud.yaml`) for automatic deployment.
- Cloned repositories from GitHub for deployment:
    - **Einstein Webpages:** [GitHub Repository](https://github.com/vishalbichkunde/einstein-webpages)
    - **Cloud YorkU Web:** [GitHub Repository](https://github.com/vishalbichkunde/cloud-yorku-web)
- Deployed applications to AWS instances:
    - `44.200.206.144`
    - `3.216.124.234`

## **Technologies Utilized**
- **AWS EC2:** Cloud infrastructure setup.
- **Ansible:** Automation framework for deployment.
- **YAML:** Scripting language for playbooks.
- **GitHub:** Source code and repository management.

## **Results and Achievements**
- Successfully configured and deployed an automated cloud infrastructure.
- Applications were deployed and tested on AWS servers.
- Achieved seamless automation using Ansible.

---
