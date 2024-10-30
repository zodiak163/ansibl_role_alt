Роль по заданию курса Альт shell

Команда для запуска playbook 
ansible-playbook start_playbook.yml

Команда для запуска playbook с  запросом пароля админа 
ansible-playbook start_playbook.yml -i inventory.yml --ask-become-pass

Пример переопределения пользователей и паролей
ansible-playbook playbook.yml -e 'rdp_users=[{"name": "user1", "password": "NewPassword1"}, {"name": "user2", "password": "NewPassword2"}]'


Список по пути /defaults/main.yml


