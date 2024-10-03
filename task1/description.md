### Task 1: Basic File and Package Management
**Objective:** Write a playbook that manages file creation and package installation on a remote node.

**Requirements:**
- Use the `file` module to create a directory `/opt/myapp`.
- Use the `copy` module to copy a configuration file from the local system to `/opt/myapp/config.cfg` on the managed node.
- Install the `nginx` package using the `apt` or `yum` module (depending on your OS).

**Key Concepts:**
- Ansible modules: `file`, `copy`, `apt`/`yum`.
