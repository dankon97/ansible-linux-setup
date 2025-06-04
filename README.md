# ⚙️ ansible-linux-setup

Ansible playbook to quickly set up a basic Linux server:

- Update system packages
- Install common tools: `htop`, `curl`, `fail2ban`
- Create a user named `daniil`

## 🧩 Requirements

- Ansible installed on your control machine
- SSH access to the target server

## 🚀 Run

```bash
ansible-playbook -i inventory.ini playbook.yml
