# ansible
Edit  your site.yaml, remove the roles that are not needed and run code below
```
   ansible-playbook -i hosts site.yaml --extra-vars "ansible_sudo_pass={{Your sudo password}}" 
```

