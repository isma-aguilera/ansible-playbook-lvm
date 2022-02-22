# ansible-playbook-lvm


Playbook Ansible para automatizar la creación de particiones primarias LVM, Volume Group, Logical Volume y para Montar/Desmontar FS.


En el archivo **ansible.cfg** definimos el inventario a utilizar y los privilegios para la ejecucion de tareas.


En el archivo **playbook.yml** se encuentran las tareas a ejecutar. **Detallo los enlaces de la documentacion:**


- [Module parted](https://docs.ansible.com/ansible/latest/collections/community/general/parted_module.html)
- [Module shell](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/shell_module.html)
- [Module lvg](https://docs.ansible.com/ansible/2.5/modules/lvg_module.html)
- [Module lvol](https://docs.ansible.com/ansible/latest/collections/community/general/lvol_module.html)
- [Module filesystem](https://docs.ansible.com/ansible/latest/collections/community/general/filesystem_module.html)
- [Module file](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/file_module.html)
- [Module mount](https://docs.ansible.com/ansible/latest/collections/ansible/posix/mount_module.html)


## RUN PLAYBOOK
---


`ansible-playbook playbook.yml -i hosts`
