# linux_project1

1. **Installation du serveur Nextcloud**  
   - Ajouter les entrées dans `/etc/hosts`.
   - Installer Apache, MariaDB, PHP, et autres dépendances nécessaires.
   - Configurer le pare-feu pour autoriser les connexions nécessaires.
   - Configurer Apache pour Nextcloud et Collabora.
   - Créer la base de données pour Nextcloud.
   - Finaliser l'installation de Nextcloud via le navigateur (création d'un compte administrateur, configuration de la base de données).

2. **Création du certificat SSL avec Let's Encrypt**  
   - Installer Certbot et générer un certificat SSL.
   - Configurer la redirection HTTP vers HTTPS.
   - Ajouter une tâche cron pour renouveler automatiquement le certificat.

3. **Installation de la suite bureautique (Collabora Online)**  
   - Ajouter les dépôts nécessaires et installer Collabora Online.
   - Configurer le serveur Collabora pour le domaine.
   - Créer et installer des certificats SSL pour sécuriser la communication entre Nextcloud et Collabora.
   - Configurer Nextcloud pour utiliser Collabora Online.

4. **Configuration de Thunderbird pour la synchronisation**  
   - Créer un mot de passe d'application pour Thunderbird (si 2FA est activé).
   - Synchroniser les carnets d’adresses (CardDAV) et les agendas (CalDAV) avec Nextcloud.
   - Configurer Thunderbird pour utiliser les services CalDAV et CardDAV de Nextcloud.

5. **Configuration d'un téléphone Android**  
   - Installer Nextcloud, OpenTasks et DAVx⁵.
   - Connecter l’application Nextcloud et configurer la synchronisation automatique des photos.
   - Configurer DAVx⁵ pour synchroniser les carnets d'adresses et les agendas avec Nextcloud.
