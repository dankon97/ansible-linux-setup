# ⚙️ ansible-linux-setup

Ansible playbook для быстрой настройки Linux-сервера:

- Обновление системы
- Установка `htop`, `curl`, `fail2ban`
- Создание пользователя `daniil`

## 📦 Запуск

```bash
ansible-playbook -i inventory.ini playbook.yml
