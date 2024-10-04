### Task 5: Configuring Multiple Nodes with Group Variables
**Objective:** Use an inventory file and group variables to configure multiple hosts.

**Requirements:**
- Define an inventory with at least two groups: `web` and `db`.
- Create group variables for the `web` group (e.g., `nginx` settings) and `db` group (e.g., `database` configuration).
- Write a playbook that uses these variables to configure both groups.
  - For the `web` group, use the `webserver` role created in Task 4.
  - For the `db` group, install `mariadb-server` or `mysql` using the `package` module.

**Key Concepts:**
- Ansible inventory.
- Group variables (`group_vars`).
- Ansible modules: `package`, custom role.
