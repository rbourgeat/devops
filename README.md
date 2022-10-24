# Documentation

- Installez préalablement **Vagrant** et **Ansible**.

- Pour lancer le projet: `vagrant up` (ou `sudo vagrant up`, Ansible aura besoin de copier/coller un fichier sur votre machine).

Vagrant va instancier 3 machines en local: 1 *master* et 2 *nodes*.

Les *playbooks* Ansible vont installer un cluster *multi-noeuds*.

Le `master-playbook.yml` va supprimer la **teinte** du noeud *master* pour déployer les nodes Wordpress.

- Pour supprimer les machines: `vagrant destroy`.

## Environnement

Ubuntu en local sur des VM.