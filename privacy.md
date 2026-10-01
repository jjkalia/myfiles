# Roster & Pay — Politique de confidentialité

*Dernière mise à jour : 1er octobre 2026*

Roster & Pay est une application personnelle destinée aux personnels navigants. Elle lit le planning de vol que vous importez et calcule, sur votre appareil, vos heures, vos frais de déplacement, vos temps de service et de repos et une estimation de paie. Elle est éditée par Khalid Jenjare, développeur indépendant.

## 1. Données traitées sur votre appareil uniquement

Les données suivantes restent sur votre appareil et ne sont envoyées à aucun serveur de l'éditeur :

- votre planning de vol, vos vols, hôtels, heures et activités importés depuis le portail équipage de votre compagnie ou depuis des fichiers PDF que vous choisissez ;
- vos fiches de paie estimées, vos saisies manuelles et vos paramètres ;
- votre carnet de vol et les relevés (PDF, Excel, CSV, photos) que vous importez ;
- vos identifiants du portail équipage, enregistrés dans le stockage sécurisé du système (Keychain sur iOS, Keystore sur Android) pour permettre la synchronisation ; ils sont transmis au portail de votre compagnie lors de la synchronisation, et servent aussi à créer votre compte dans l'application (voir section 2) ; l'éditeur ne peut pas lire votre mot de passe. Sur le portail, l'application ne fait que ce que vous pouvez déjà faire vous-même sur son site web : consulter votre planning, vos documents et, comme le site le permet à tout navigant, le planning d'un collègue pour préparer un échange de vols ; elle n'y modifie rien. Le planning d'un collègue ainsi consulté reste sur votre appareil comme le vôtre et n'est transmis à aucun serveur de l'éditeur ;
- votre position, utilisée uniquement pour afficher la météo locale et les horaires de prière ; elle n'est ni enregistrée ni transmise.

Vous pouvez exporter une sauvegarde de ces données vers un fichier et l'effacer à tout moment depuis le menu de l'application.

## 2. Données transmises à des services en ligne

L'application utilise Firebase (Google) pour trois fonctions :

- **Compte** : votre compte est créé sans votre adresse e-mail personnelle. L'application fabrique un identifiant technique à partir de votre identifiant du portail et du type d'appareil, et utilise votre mot de passe du portail comme mot de passe de ce compte (Firebase Authentication). Firebase ne conserve ce mot de passe que sous une forme chiffrée irréversible ; l'éditeur n'y a pas accès.
- **Version installée** : votre identifiant du portail, la version de l'application et la date de dernière utilisation sont enregistrés (collection `app_users`) afin de vous proposer les mises à jour.
- **Rapports de plantage** : en cas d'incident, un rapport technique anonymisé est envoyé à Firebase Crashlytics pour corriger l'application. Il ne contient ni votre planning ni votre paie.

Aucune donnée n'est vendue, ni utilisée à des fins publicitaires, ni croisée avec d'autres services. L'application ne contient ni publicité ni outil de suivi.

## 3. Suppression du compte et des données

Depuis le menu de l'application, section Compte :

- **Déconnexion** ferme la session et efface les identifiants du portail du stockage sécurisé ;
- **Supprimer mon compte** supprime votre compte Firebase et le document qui vous est associé (`app_users`). Les données locales restent sur votre appareil jusqu'à ce que vous les effaciez ou désinstalliez l'application.

## 4. Sécurité

Les échanges avec le portail équipage et avec Firebase sont chiffrés (HTTPS). Les identifiants du portail sont stockés dans le stockage sécurisé du système.

## 5. Enfants

L'application s'adresse à des professionnels adultes et ne collecte sciemment aucune donnée d'enfants.

## 6. Contact

Pour toute question ou demande concernant vos données : jjkalia@gmail.com

---

# Roster & Pay — Privacy Policy

*Last updated: October 1, 2026*

Roster & Pay is a personal app for flight crew members. It reads the flight roster you import and computes, on your device, your hours, travel allowances, duty and rest times and a pay estimate. It is published by Khalid Jenjare, an independent developer.

## 1. Data processed on your device only

The following data stays on your device and is never sent to any server of the publisher:

- your roster, flights, hotels, hours and activities imported from your airline's crew portal or from PDF files you choose;
- your estimated payslips, manual entries and settings;
- your logbook and the records (PDF, Excel, CSV, photos) you import;
- your crew-portal credentials, stored in the system's secure storage (Keychain on iOS, Keystore on Android) to allow synchronisation; they are sent to your airline's portal when synchronising, and also used to create your account in the app (see section 2); the publisher cannot read your password. On the portal, the app only does what you can already do yourself on its website: view your roster, your documents and, as the site allows any crew member, a colleague's roster to prepare a flight swap; it changes nothing there. A colleague's roster viewed this way stays on your device like your own and is never sent to any server of the publisher;
- your location, used only to show local weather and prayer times; it is neither stored nor transmitted.

You can export a backup of this data to a file and erase it at any time from the app menu.

## 2. Data sent to online services

The app uses Firebase (Google) for three purposes:

- **Account**: your account is created without your personal e-mail address. The app derives a technical identifier from your crew-portal login and your device type, and uses your crew-portal password as the password of this account (Firebase Authentication). Firebase keeps that password only in an irreversible encrypted form; the publisher has no access to it.
- **Installed version**: your crew-portal login, the app version and the date of last use are stored (`app_users` collection) in order to offer you updates.
- **Crash reports**: in case of a failure, an anonymised technical report is sent to Firebase Crashlytics to fix the app. It contains neither your roster nor your pay.

No data is sold, used for advertising or combined with other services. The app contains no advertising and no tracking tool.

## 3. Deleting your account and data

From the app menu, Account section:

- **Sign out** closes the session and erases the portal credentials from secure storage;
- **Delete my account** deletes your Firebase account and the document linked to it (`app_users`). Local data remains on your device until you erase it or uninstall the app.

## 4. Security

Exchanges with the crew portal and with Firebase are encrypted (HTTPS). Portal credentials are kept in the system's secure storage.

## 5. Children

The app is intended for adult professionals and does not knowingly collect any data from children.

## 6. Contact

For any question or request about your data: jjkalia@gmail.com
