## Laboratorio para reunir datos de un hosts y crear tareas de los datos recogidos
1. El módulo setup de Ansible recupera datos de sistemas.

        ansible serverX -m setup
2. Verificar la sintaxis del archivo setup_facts.yml
        
        ansible-playbook --syntax-check setup_facts.yml

3. Ejecutar el playbook setup_facts.yml

        ansible-playbook setup_facts.yml

