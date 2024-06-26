# vmware-proxmox

graph TD;
    A[Projet SAFRAN]
    B[Phase 1 : Planification]
    B1[Réunion de lancement du projet]
    B2[Analyse des besoins]
    B3[Définition des objectifs et du scope]
    B4[Sélection des outils et technologies]

    A --> B
    B --> B1
    B --> B2
    B2 --> B3
    B --> B4
    
    C[Phase 2 : Virtualisation et Consolidation]
    C1[Conception de l'architecture]
    C2[Configuration initiale]
    C3[Migration des données]
    C4[Tests et validation]
    C5[Optimisation des ressources]

    A --> C
    C --> C1
    C --> C2
    C --> C3
    C --> C4
    C --> C5
    
    D[Phase 3 : Surveillance et Optimisation]
    D1[Installation de Zabbix]
    D2[Surveillance des indicateurs]
    D3[Mise en place de la gestion de l'énergie]
    D4[Configuration des alertes]
    D5[Génération de rapports]

    A --> D
    D --> D1
    D --> D2
    D --> D3
    D --> D4
    D --> D5
    
    E[Phase 4 : Validation et Déploiement Final]
    E1[Tests finaux]
    E2[Formation des équipes]
    E3[Déploiement sur production]
    E4[Suivi post-déploiement]

    A --> E
    E --> E1
    E --> E2
    E --> E3
    E --> E4
    
    F[Phase 5 : Clôture du Projet]
    F1[Réunion de clôture]
    F2[Documentation finale]

    A --> F
    F --> F1
    F --> F2

