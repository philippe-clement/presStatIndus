# DESSIN

---

## Présentation

- gestion des enquêtes annuelles de production 
- utilisateurs principaux : SSNE et ESPRI
- autres utilisateurs : EMBRUN, ESANE, ...
- 3 enquêtes pour un echantillon totale de 36000 ul 
- 5 IHM, 81 batchs, 1 api(WS)
- 1 base de données communes en Oracle actuellement
- Technologie identtique JAVA/ Struts2  sauf FUL ...


---

## EAP / COTRANE 

- collecte sur le site Coltrane depuis 2017
- Pas entrée dans la filière POGUES/ENO 
- questionnaires trop personnalisable + tableaux avec unités différentes en ligne
- Risque en cas de grosses modifications du questionnaire
- Ajout de question pour le moment possible si on peut passer par POGUES (question générale)
- Pb récupérant entre adresses SIRUS et COLTRANE non compatibles


---
## IAE

- Infrastructure Amont des Enquêtes
- Repertoire de nomenclature des produits pour l'EAP (et aussi l'EMB)
- 1 IHM , 1 batch
- Beaucoup de programmes en self pour fournitures aux partenaires.
- Forte utilisation en septembre/octobre : validation des prodeap

---

## FUL

- Héritage du répertoire d'unités statisitiques du SESSI
- 1 IHM, 27 batchs, 1 WS
- Utlisation d'un frameword maison MVC à l'IHM qui rend la maintenance exotique.
- Récupération des données de SIRENE/SIRUS/OCSANE
- Récupération des echantillons du DMS
- Mise à jour des données SIRUS gràce au AVISIRUS
- Récupération des contacts COLTRANE au format XML
- Webservice pour gérer l'echantillon des EMB et visbilité contact Coltrane


---

## OASIS

- Outil pour la gestion de la collecte des EAP
- 1 IHM, 19 batchs
- Récupération des données de FUL et IAE pour constituer les questionnaires
- Production de fichier de personnalisation pour COLTRANE
- Intégration des réponses sur COLTRANE
- Controle et Redressement à l'aide d'une module LSE (Langage de Spécification d'Ésane)
- Utilisation de WS : IGESA , WS calcul d'APE.
- Proposition de changement d'APE en fonction des réponses EAP
- Bascule des questionnaires validées pour CALVADOS : versement dans la BEC : Base Elementaire de Calcul

---

## OASIS/ENCORE

- ENquete COntrôle et REdressement
- Contrôle et redressements de l'Enquête annuelle
- Utilisation du LSE
- Pseudo-code écrit par Statisticiens
- Compilateur pour générer du code JAVA
- Intégration des classes JAVA dans OASIS
- Avantage : ca marche bien ...
- Inconvénient : si Problème ou modification du questionnaire, ca serait compliqué à expertiser

--

## OASIS/c'est pas fini 

- Récupération des données Externes 
- Affichage dans OASIS
- Confidentialité de ces données à garantir
- Utilisation dans d'autres applications CALVADOS


---

## CALVADOS

- CALcul et VALidation des DOnneeS
- 1 IHM, 33 Batchs
- Utlise les données validées de l'EAP + FUL + IAE
- Traitement de la nom-réponse (imputation)
- Utilisation de la BEC pour Agregation
- IHM pour validation les agrégats
- Première publication d'indicateur à Eurostat au 30 juin
- Utilisation d'une Base Elémentaire de Diffusion pour garder ces publications



---

## ORESTE

- Gestion des restructuration
- 1 IHm, A batch
- échange avec CITRUS dans les 2 sens
