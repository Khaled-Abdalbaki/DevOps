# DevOps

## Automation avec ansivble
pour executer ansible on utilise la command suivant : 

ansible command line:
-database machine:
DevOps> ansible-playbook -u root -i hosts.ini Ansible/database.yaml

--backend machine:
DevOps> ansible-playbook -u root -i hosts.ini Ansible/back-end.yaml


ansible-playbook -u ubuntu -i inventory/hosts.ini ../tp-Ansible/playbook.yml


les ip address des machines sont presenter dans le fishiers hosts.ini 

pour acceder au gitlab server il suffit de taper sur le navigateur web l'ip du server git lab : 45.79.202.35 (la machine et arreter)


j'ai bien installer les dependencies sur les machines , il me rest a faire le ci cd.


mysql -u root -p
CREATE USER 'remoteuser'@'%' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON *.* TO 'remoteuser'@'%';