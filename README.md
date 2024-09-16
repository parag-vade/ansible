# ansible
Ansible is an open-source automation tool that simplifies configuration management, application deployment, and task automation. It works by connecting to nodes over SSH without requiring agents, making it lightweight and easy to use.

**Key Components of Ansible:**

1. Playbooks: YAML files that define a series of tasks to be executed on remote nodes.
2. Inventory: A file that lists the hosts (servers or nodes) where tasks will be executed.
3. Modules: Units of work that Ansible executes, like installing packages, managing files, or configuring systems.
4. Roles: A structured way of grouping tasks, handlers, files, and variables into reusable components.
5. Tasks: Actions executed in playbooks (e.g., install a package, start a service).
6. Handlers: Triggered when notified, commonly used for restarting services.
7. Variables: Values that can be reused across playbooks or tasks.

**Use Cases**
1. Configuration Management: Install packages, configure files, and manage users.
2. Application Deployment: Automate the deployment process of applications across multiple environments.
3. Infrastructure as Code (IaC): Provision infrastructure resources like servers, databases, and networking.

**Sample Ansible Playbook for Installing Apache Web Server**
![image](https://github.com/user-attachments/assets/54614873-a473-437c-9adc-93220ae74ed3)


**Inventory File Example (hosts)**

![image](https://github.com/user-attachments/assets/26237c3d-8888-41d5-b25b-a2bede210123)

**Command to Run the Playbook:**
ansible-playbook -i hosts webserver.yml


**Use Cases:**
CI/CD Integration: Automate deployments in a pipeline.
Cloud Provisioning: Manage cloud resources on platforms like AWS, GCP, Azure.
Security Automation: Apply patches, manage firewall rules.

Ansible is highly versatile and widely used in DevOps for automating IT workflows, ensuring consistency, and reducing manual errors.









