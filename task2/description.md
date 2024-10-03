### Task 2: User Management with Ansible Vault
**Objective:** Manage users and secure sensitive data using Ansible Vault.

**Requirements:**
- Create a user named `ansible_user` using the `user` module.
- Set the password for the user using Ansible Vault to encrypt it.
- Use the `ansible.builtin.debug` module to print the username to confirm the user was created.

**Key Concepts:**
- Ansible Vault to store sensitive data (passwords).
- Ansible module: `user`, `debug`.
