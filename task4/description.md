### Task 4: Create an Ansible Role for Web Server
**Objective:** Create and use a role to deploy a web server.

**Requirements:**
- Create an Ansible role named `webserver` that:
  - Installs `nginx` or `httpd`.
  - Copies an `index.html` file.
  - Starts and enables the web server.
- Call the `webserver` role from your playbook and apply it to the target node.

**Key Concepts:**
- Ansible roles (folder structure, tasks, handlers).
- Ansible modules: `package`, `service`, `copy`.
