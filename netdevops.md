# Présentation NetdevOps => concept
 - reposant sur Agile => concept non projet car forte fédération équipe et utilisateurs.
    - tests unitaires => automatisation.
 - déploiement et intégration continue => lié à un contexte (librairies, environnement.)
 - implique l'utilisation de containers => kubernetes, docker.
 - DevOps   => attitude permettant de rapprocher concepteurs ingénierie projet et exploitants. Communiquant, médiateur 
 entre exploitants et ingénierie de projets.
            => implique l'automatisation.

# Historique 
    => 2013 : human driven automation, scripts d'automatisations.
    => event driven automation => information analysée qui remonte un événement génère une action humaine.
    => machine driven automation => machine qui prend la décision binaire, sinon humain.
    => self driving automation => IA : machine prend la décision, machine learning, deep learning => réseaux de neurones.

# acteurs majeurs
    - Juniper => opensource
    - Arista => opensource
    - Cisco => société DevNet, qui développe l'automatisation en opensource (Nexus 9000V).
    - Cumulus => logiciel base Debian, repose sur des environnements matériels différents. (Vmware pour équipements réseaux)

 # switch virtuel Juniper
    - Control Plane 
    - Data Plane

    control plane <=> data plane =====> lien em0

# VirtualBox 5.2 (plus de support 64 bits avec version 6)+ Vagrant
    - Vagrant

# Creation compte GitHub
    - account : @JBarb1er

# JSnapy 
    - permet de tests unitaires, migration (pre-check, post-check, etc...)

# Ansible 2.7 :
 - modules agnostiques
 - cli_command permet d'executer des commandes arbitraires sur les équipements réseaux.
 - cli_config permet de pousser une conf texte vers n'importe quel type d'équipements.
 - network modules => voir doc constructeurs
 - Galaxy ansible => voir Juniper
