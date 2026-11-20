# Politique de confidentialité — Sumo Bot

Dernière mise à jour : 20 novembre 2026

## 1. Présentation

Sumo Bot ne collecte que les données nécessaires à ses fonctionnalités, ne les vend jamais et ne les partage avec personne en dehors de Discord.

Cette politique s'applique au bot Discord **Sumo Bot** (identifiant d'application Discord : STG - Sécurité) sur tous les serveurs où il est installé. Le responsable du traitement est le créateur du bot, Naeroz. En utilisant un serveur où Sumo Bot est présent, ou en utilisant ses commandes, tu acceptes cette politique.

Sumo Bot fonctionne uniquement dans Discord. Il est donc aussi soumis à la [politique de confidentialité de Discord](https://discord.com/privacy) et aux [conditions d'utilisation des développeurs Discord](https://discord.com/developers/docs/policies-and-agreements/developer-terms-of-service).

## 2. Données collectées

Sumo Bot enregistre surtout des **identifiants Discord** (numéros de membres, de serveurs, de salons et de rôles) et des données liées aux fonctionnalités activées par chaque serveur. Il ne collecte ni adresse e-mail, ni mot de passe, ni adresse IP.

| Fonctionnalité | Données enregistrées |
| --- | --- |
| Statistiques d'activité (`+statut`, `+prune`) | Nombre de messages et temps passé en vocal par jour et par heure. Pas le contenu des messages. |
| Niveaux et XP | XP de chaque membre et heure de son dernier gain d'XP |
| Modération | Avertissements, casier des sanctions (type, raison, auteur, date), notes de modération, bannissements temporaires |
| Tickets de commande et de support | Numéro du ticket, client, staff qui le prend en charge, formule choisie, prix, moyen de paiement choisi, réponses aux questions, notes internes du staff |
| Transcripts de tickets | Contenu des messages du ticket, envoyé sous forme de fichier dans le salon de logs choisi par le serveur |
| Vouchs | Note de 1 à 5 et avis laissés par le client |
| PayPal des créateurs (`+paypal`) | Pseudo ou lien PayPal.me que le créateur a choisi d'enregistrer |
| Candidatures | Réponses aux questions de la candidature et décision du staff |
| Modmail et `+feedback` | Messages envoyés au staff ou au créateur du bot |
| Invitations | Qui a invité qui, nombre d'invitations |
| Giveaways, sondages, suggestions, rappels, AFK | Participants, votes, texte de la suggestion, du rappel ou du statut AFK |
| `+snipe` et `+editsnipe` | Dernier message supprimé ou modifié d'un salon, gardé **en mémoire seulement** pendant 2 heures, jamais écrit sur le disque |
| Configuration des serveurs | Réglages choisis par les administrateurs : salons, rôles, messages, commandes personnalisées, réponses automatiques, messages programmés |
| Sauvegardes de serveur (`+backupserveur`) | Structure du serveur : noms et réglages des rôles et des salons. Pas les messages. |
| Journaux techniques du développeur | Commandes utilisées, erreurs, arrivée ou départ du bot d'un serveur, actions de modération. Pas le contenu des messages des membres. |

Sumo Bot n'utilise pas le statut en ligne ni les activités des membres (jeux, musique…) : il ne les lit pas et ne les enregistre pas.

## 3. Pourquoi ces données sont utilisées

Les données servent uniquement à faire fonctionner les commandes du bot et à protéger les serveurs. Elles ne servent jamais à de la publicité, à du profilage commercial ou à entraîner une intelligence artificielle.

Sumo Bot utilise deux autorisations spéciales de Discord, appelées *intents privilégiés* :

- **Contenu des messages** : lire les commandes écrites avec le préfixe (par exemple `+help`), détecter les liens, le spam et les mots interdits, répondre aux réponses automatiques, faire respecter les salons réservés aux médias, et créer les transcripts de tickets et le modmail. Le contenu est lu au moment où le message arrive. Il n'est enregistré que dans les cas listés au point 2.
- **Membres du serveur** : messages de bienvenue et de départ, rôle automatique, anti-raid (âge des comptes), suivi des invitations, compteurs de membres, remerciement des boosts et recherche des membres inactifs.

Les journaux techniques servent au créateur à corriger les bugs et à repérer les abus du bot.

## 4. Durée de conservation

Les données sont gardées tant que Sumo Bot est utilisé sur le serveur concerné, sauf les cas plus courts ci-dessous. Elles peuvent être supprimées à tout moment sur demande (point 6).

| Donnée | Durée |
| --- | --- |
| `+snipe` et `+editsnipe` | 2 heures, en mémoire seulement |
| Ticket ouvert | Supprimé à la fermeture du ticket. Seul le transcript reste, dans le salon de logs du serveur. |
| Casier des sanctions | Les 100 dernières sanctions par membre |
| Feedbacks | Les 300 derniers |
| Journaux techniques | Fichiers tournants : les plus anciens sont effacés automatiquement |
| Sauvegardes automatiques | Une copie par jour, remplacée au fil du temps, accessible seulement au créateur du bot |

Les messages envoyés par le bot dans les salons d'un serveur (logs, transcripts, annonces) appartiennent à ce serveur. Ses administrateurs peuvent les supprimer à tout moment.

## 5. Partage, stockage et sécurité

Les données ne sont **jamais vendues ni partagées** avec une entreprise ou une autre personne.

- **Stockage** : fichiers sur le serveur d'hébergement du bot, chez Bot-Hosting. L'accès est réservé au créateur du bot.
- **Accès** : seuls le créateur et les co-propriétaires qu'il désigne peuvent voir les journaux techniques et les sauvegardes. Sur chaque serveur, les administrateurs et le staff voient les données de leur propre serveur (sanctions, tickets, candidatures) selon leurs permissions.
- **Paiements** : Sumo Bot ne traite aucun paiement et ne voit aucune donnée bancaire. Il affiche seulement les adresses ou liens de paiement configurés par le serveur. Le paiement se fait directement sur PayPal, Revolut ou la blockchain concernée.
- **Sites externes** : pour les notifications `+notif`, le bot consulte les flux publics de YouTube et l'API de Twitch. Il n'y envoie aucune donnée sur les membres.
- **Chiffrement** : toutes les données enregistrées sur le disque (fichiers de données, statistiques, journaux techniques et sauvegardes) sont chiffrées au repos (Fernet : AES-128 et HMAC-SHA256). La clé est gardée à part, dans la configuration privée du bot.
- **Sécurité** : les fichiers sont écrits de façon sécurisée pour éviter les pertes, et une sauvegarde chiffrée est faite chaque jour. Aucun système n'est sûr à 100 %. En cas de fuite de données, les serveurs concernés seront prévenus.

## 6. Tes droits et contact

Tu peux demander à tout moment d'accéder à tes données, de les corriger ou de les faire supprimer. La demande est traitée sous 30 jours.

- **Pour faire une demande** : utilise la commande `+feedback` en précisant ta demande. Le créateur te répondra en message privé.
- **Limite** : les sanctions et données de modération d'un serveur peuvent être gardées si les administrateurs de ce serveur en ont besoin pour sa sécurité. Ta demande leur sera alors transmise.
- **Administrateurs** : retirer Sumo Bot d'un serveur arrête toute collecte sur ce serveur. Pour faire effacer toutes les données d'un serveur, contacte le créateur avec `+feedback`.
- **Réclamation** : si tu habites dans l'Union européenne, tu peux aussi déposer une plainte auprès de la [CNIL](https://www.cnil.fr/fr/plaintes) ou de l'autorité de protection des données de ton pays.

Pour utiliser Sumo Bot, tu dois avoir l'âge minimum demandé par Discord dans ton pays.

**Modifications** : cette politique peut être mise à jour. La date en haut de la page indique la dernière version. Les changements importants sont annoncés avec la commande `+maj`.
