# Cohérence cardiaque — pages publiques

Site de présentation et politique de confidentialité de l'application Android
**Cohérence cardiaque** (« Heart Coherence », `com.coherencecardiaque.app`), publiés via
GitHub Pages. Le code de l'application est ailleurs et reste privé.

| Page | URL |
| --- | --- |
| Accueil | https://olivier3dprint.github.io/coherencecardiaque/ |
| Confidentialité (FR) | https://olivier3dprint.github.io/coherencecardiaque/confidentialite.html |
| Privacy (EN) | https://olivier3dprint.github.io/coherencecardiaque/privacy.html |
| app-ads.txt | https://olivier3dprint.github.io/coherencecardiaque/app-ads.txt |

L'application ouvre la page de sa langue (`privacy_policy_url` dans `strings.xml`) :
`confidentialite.html` en français, `privacy.html` en anglais.

La page d'accueil est bilingue (bouton de langue, `?lang=en` pour forcer l'anglais,
sinon langue du navigateur). Les captures de `images/` sont des réductions (540 × 1080,
JPEG) des captures de la fiche Play, faites dans le dépôt privé
(`Play Store/visuels/capture-N_fr|en.png`, captures 1, 2, 4, 5 et 6) : si celles-ci
changent, réexportez-les ici. `partage-fr.jpg` / `partage-en.jpg` (aperçu des liens
partagés) sont les images de présentation 1024 × 500 de la fiche, `icone.png` l'icône
512 réduite en 192.

`app-ads.txt` déclare l'éditeur AdMob (même compte que les autres applications). AdMob ne
le lit qu'à la racine du domaine déclaré comme site du développeur sur la fiche Play ; ici
il n'est donc utile que si ce site-là est déclaré, comme pour les autres applications.

## Activer GitHub Pages

*Settings* › *Pages* › Source : **Deploy from a branch**, branche `main`, dossier
`/ (root)`. La mise en ligne prend une minute environ.

## Tenir la politique à jour

Elle décrit le comportement réel de l'application au 1er novembre 2026 : historique et
réglages stockés sur l'appareil uniquement, sauvegarde par fichier à l'emplacement choisi
par l'utilisateur, aucune localisation, aucune mesure (ni fréquence cardiaque, ni capteur,
ni caméra), et un seul échange avec un tiers : la publicité AdMob.

Elle devra être révisée si l'application gagne un outil de mesure d'audience ou de
remontée de plantages, un compte utilisateur, des achats intégrés, la lecture de
capteurs (fréquence cardiaque, caméra) ou une synchronisation (Health Connect, montre…).

Les réponses du formulaire *Sécurité des données* de la Play Console doivent rester
cohérentes avec ces pages : modifier l'un impose de vérifier l'autre.

Les textes respectent le vocabulaire de l'application : se détendre, faire une pause,
gérer le stress du quotidien ; aucun effet médical annoncé.

Responsable du traitement : Olivier Popiers — `oliviertheandroidmaker@gmail.com`
