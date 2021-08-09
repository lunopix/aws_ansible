Ce projet comprend 3 playbooks permettant de créer une machine EC2 t2.micro avec l'image Amazon Lunix 2 dans chaque réseau que vous aurez défini dans AWS. Les réseaux doivent être dans des zones de disponibilité différentes. Il ne doit y avoir deux réseaux ou plus appartenant à la même zone de disponibilité.

Modifier la liste des réseaux dans le fichier vars.yml

Créer un nouveau fichier keyfiles.yml avec les variables ci-dessous ainsi que leur valeur.

AWS_ACCESS_KEY_ID: AWS_SECRET_ACCESS_KEY: AWS_REGION:

Executez le playbook DeployerEC2.yml en premier

Executez le playbook HTTPD_PHP.yml en second

Executez le playbook DeployerELB.yml en dernier
