```yaml
---
- name: Un playbook muy muy sencillo
  # A quienes se les va a operar  Canilo
  hosts: all
  tasks:
    - name: Dame un mensaje
      ansible.builtin.debug:
        msg: "Bienvenido al mundo de Ansible"

```
