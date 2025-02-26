# Nginx Website Ansible Playbook

This playbook sets up a basic Nginx web server with a simple HTML page.

## Usage

1. Install requirements:
   ```bash
   brew install ansible
   ```

2. Run the playbook:
   ```bash
   ansible-playbook -i inventory.ini first-playbook.yml
   ```

3. Visit http://localhost:8080 to see the website. 
