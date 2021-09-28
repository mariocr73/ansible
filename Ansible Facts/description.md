## Laboratorio para reunir datos de un hosts y crear tareas de los datos recogidos
1. El módulo setup de Ansible recupera datos de sistemas.

        ansible serverX -m setup
2. Verificar la sintaxis del archivo setup_facts.yml
        
        ansible-playbook --syntax-check setup_facts.yml

3. Ejecutar el playbook setup_facts.yml

        ansible-playbook setup_facts.yml

4. Verificar que el servicio no se encuentra en ejecución en nuestro hots de inventario (ServerX)

        ansible servera.lab.example.com -m command -a 'systemctl status httpd'

5. Verificar la sintaxis del archivo playbook.yml

        ansible-playbook --syntax-check playbook.yml

6. Ejecutar el playbook playbook.yml

        ansible-playbook playbook.yml

7. Verificar con ` systemctl ` para determinar si el servicio **httpd** se está ejecutando

        ansible servera.lab.example.com -m command -a 'systemctl status httpd'
