### MedIT - Débogage et optimisation d'un site WordPress pour le secteur médical

# Description du projet

MedIT est un site WordPress dédié à une PME spécialisée dans les systèmes informatiques pour le secteur médical. Suite à des modifications non réussies, le site a rencontré plusieurs problèmes de fonctionnement. Le projet a pour objectif de diagnostiquer et corriger ces erreurs, d'améliorer la stabilité du site et de documenter les solutions pour éviter des erreurs similaires à l'avenir.

# Objectifs du projet

-	Déboguer et corriger les erreurs survenues après une tentative de mise à jour du site par le client.
-	Restaurer l'accès complet au site et rétablir les fonctionnalités principales.
-	Documenter les corrections via un cahier de recette, listant les erreurs rencontrées, les solutions apportées et les recommandations pour prévenir les futurs problèmes.
-	Apprendre au client les tests unitaires et fonctionnels, avec un guide concis expliquant leur utilité, leur fonctionnement et leur application.
Fonctionnalités principales
-	Cahier de recette : Répertorie les erreurs identifiées, les corrections effectuées, et le comportement attendu des fonctionnalités.
-	Guide sur les tests : Un document d’explication sur les tests unitaires et fonctionnels, adapté aux besoins de l’équipe technique de MedIT pour une meilleure gestion des bugs.
-	Debugging avancé : Utilisation des outils WordPress tels que wp-debug pour identifier les erreurs et des outils comme la console navigateur pour les erreurs JavaScript.
Technologies utilisées
-	WordPress
-	PHP
-	JavaScript
-	HTML/CSS
-	Elementor pour la personnalisation des pages
-	Debugging Tools : wp-debug, PhpMyAdmin, var_dump, console du navigateur
-	GitHub pour la gestion des versions et la documentation des correctifs
Étapes de réalisation
Étape 1 : Clonage du site en local
-	Téléchargez l'archive du site et le fichier SQL de la base de données.
-	Importez la base de données dans PhpMyAdmin et configurez le fichier wp-config.php pour correspondre aux identifiants de connexion à votre environnement local.
Étape 2 : Restauration de l’accès au site
-	Activez le mode wp-debug pour identifier les erreurs initiales et résoudre les problèmes de chargement du site.
-	Assurez-vous que l’interface back-office est accessible, et que les pages principales peuvent être visualisées.
Étape 3 : Création du cahier de recette
-	Reproduisez chaque bug signalé et notez les observations dans le cahier de recette.
-	Documentez les solutions mises en place et les vérifications effectuées pour valider les correctifs.
Étape 4 : Correction des erreurs d’édition Elementor
-	Analysez les erreurs liées à Elementor, identifiez les fichiers de scripts bloquant et corrigez les appels Ajax si nécessaire.
Étape 5 : Débogage de la modale
-	Corrigez le problème de fermeture de la popup, l’affichage du formulaire de contact, et le lien Google Maps.
-	Utilisez la console du navigateur pour repérer les erreurs JavaScript et appliquer les correctifs nécessaires.
Étape 6 : Ajustement du bouton de contact
-	Modifiez la structure du code CSS/HTML pour centrer et aligner correctement le bouton de contact dans le menu.
Étape 7 : Rédaction d'un guide sur les tests unitaires et fonctionnels
-	Créez un document expliquant la différence entre les tests unitaires et fonctionnels, et les contextes d'application pour chacun.
-	Détaillez les avantages de l'utilisation des tests pour maintenir et optimiser le site MedIT.
Défis techniques et solutions
-	Erreur de chargement Elementor : Résolu en réinitialisant les scripts et en vérifiant les appels Ajax bloqués.
-	Débogage de la Popup : Modifications apportées aux scripts JavaScript pour restaurer la fonctionnalité de fermeture et vérifier les liaisons dynamiques avec Google Maps.
-	Documentation complète : Création d'un cahier de recette pour formaliser les corrections et s'assurer d'une bonne communication avec le client.
