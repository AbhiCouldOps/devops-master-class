Pipelines, Continuous Integration, Continuous Deployment, Continuous Delivery

- Commit -> Unit Tests > Code Quality Checks > Integration Tests > Package > Deploy App > Manual Testing > Approval > Next Environment
- Tools - Azure DevOps and Jenkins
- Build - Building a deployable version of application. Tools - Maven, Gradle, Docker, WASM, What is used for Python?, Anything else for JavaScript?
- Deployment - Putting new applications or new versions of application live. Tools - CI/CD Tools. Application Deployable - ear, war, container image

IAAC

- Done Manually - Provision Server, Install Java, Install Tomcat, Deploy Application
  - Everytime you create a server, this needs to be done manually. What if Java version needs to be updated? A security patch needs to be applied?
  -
- Code Your Infra - Treat Infrastructure the same way as application code
  - Infra team focuses on value added work (instead of routine work)
  - Less Errors and Quick Recovery from Failures
  - Servers are Consistent (Avoids Configuration Drift)
- Tools - Ansible and Terraform
- Create Template, Provision Servers(Enabled by Cloud), Install Software, Configure Software, Deploy Application
- Provisioning Tools - Get new server ready with networking capabilities - CloudFormation and Terraform - Designed to provision the servers themselves (as well as the rest of your infrastructure, like load balancers, databases, networking configuration, etc). You can use precreated images created using Packer and AMI (Amazon Machine Image).
- Configuration management tools - Chef, Puppet, Ansible, and SaltStack - Designed to install and manage software on existing servers.
