# DESSIN

---

## Présentation

- Gestion des enquêtes annuelles de production 
- Utilisateurs principaux : SSNE et ESPRI
- Autres utilisateurs : EMBRUN, ESANE, ...
- 3 enquêtes pour un echantillon total de 36000 ul 
- 4 IHM, 81 batchs, 1 api(WS)
- 1 base de données commune en Oracle actuellement
- Technologie identique JAVA/Struts2 sauf FUL ...


---

## EAP / COLTRANE 

- Collecte sur le site Coltrane depuis 2017
- Collecte de février à septembre
- Pas entrée dans la filière POGUES/ENO 
- Questionnaires trop personnalisables + tableaux avec unités différentes en ligne
- Risque en cas de grosses modifications du questionnaire
- Ajout de question pour le moment possible si on peut passer par POGUES (question générale)
- Problèmes récurrents entre adresses SIRUS et COLTRANE non compatibles


---

## IAE

- Infrastructure Amont des Enquêtes
- Repertoire de nomenclature des produits pour l'EAP (et aussi l'EMB)
- 1 IHM , 1 batch
- Beaucoup de programmes en self pour fournitures aux partenaires.
- Forte utilisation en septembre/octobre : validation des prodeap

---

## FUL

- Héritage du répertoire d'unités statistiques du SESSI
- 1 IHM, 27 batchs, 1 WS
- Utlisation d'un framework maison MVC pour l'IHM qui rend la maintenance exotique.
- 2 schémas dans la bdd pour gérer l'archivage


---

## FUL(suite)

- Récupération des données de SIRENE/SIRUS/OCSANE/PROFILAGE
- Récupération des échantillons du DMS
- Mise à jour des données SIRUS gràce aux AVISIRUS
- Récupération des contacts COLTRANE 
- Webservice pour gérer l'echantillon des EMB et visbilité contacts Coltrane

---

## OASIS

- Outil pour la gestion de la collecte des EAP
- 1 IHM, 19 batchs
- Récupération des données de FUL et IAE pour constituer les questionnaires
- Production de fichiers de personnalisation pour COLTRANE
- Intégration des réponses sur COLTRANE
- Contrôles et Redressements à l'aide d'un module LSE (Langage de Spécification d'Ésane)
- Versements dans la BEC : Base Elémentaire de Calcul pour CALVADOS

---

## OASIS/ENCORE

- ENquete COntrôles et REdressements
- Contrôles et redressements de l'Enquête Annuelle de Production
- Utilisation du LSE
- Pseudo-code écrit par des Statisticiens
- Compilateur pour générer du code JAVA
- Intégration des classes JAVA dans OASIS
- Avantage : ca marche bien ...
- Inconvénient : si Problème ou modification du questionnaire, ca serait compliqué à expertiser

---

## OASIS/c'est pas fini 

- Utilisation de WS : IGESA , WS calculs d'APE.
- Récupération des données externes pour affichage dans Oasis.
- Gestion de la confidentialité de ces données à garantir.
- Utilisation des données externes dans d'autres applications (CALVADOS).


---

## CALVADOS

- CALcul et VALidation des DOnnéeS
- 1 IHM, 33 Batchs
- Utlise les données validées de l'EAP 
- Traitement de la non-réponse (imputation)
- Utilisation de la BEC pour agrégation
- IHM pour validation des agrégats
- Première publication d'indicateurs à Eurostat au 30 juin
- Utilisation d'une Base Elémentaire de Diffusion 
- Code très 'sql' et complexe à comprendre mais efficace



---

## ORESTE

- Gestion des restructurations
- 1 batch
- échanges avec CITRUS pour récupérer les restructuration
- reflexion pour l'utlisation du WS Citrus en remplacement du batch.
