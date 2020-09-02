# DESSIN

---

## Présentation

- Gestion des enquêtes annuelles de production 
- Utilisationtilisateurs principaux : SSNE et ESPRI
- Autres utilisateurs : EMBRUN, ESANE, ...
- 3 enquêtes pour un echantillon totale de 36000 ul 
- 5 IHM, 81 batchs, 1 api(WS)
- 1 base de données commune en Oracle actuellement
- Technologie identique JAVA/Struts2 sauf FUL ...


---

## EAP / COTRANE 

- Collecte sur le site Coltrane depuis 2017
- Collecte de février à septempbre
- Pas entrée dans la filière POGUES/ENO 
- Questionnaires trop personnalisables + tableaux avec unités différentes en ligne
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

- Héritage du répertoire d'unités statistiques du SESSI
- 1 IHM, 27 batchs, 1 WS
- Utlisation d'un framework maison MVC pour l'IHM qui rend la maintenance exotique.
- 2 schémas dans la bdd pour gérer l'archivage


---

## FUL(suite)

- Récupération des données de SIRENE/SIRUS/OCSANE
- Récupération des échantillons du DMS
- Mise à jour des données SIRUS gràce aux AVISIRUS
- Récupération des contacts COLTRANE 
- Webservice pour gérer l'echantillon des EMB et visbilité contact Coltrane

---

## OASIS

- Outil pour la gestion de la collecte des EAP
- 1 IHM, 19 batchs
- Récupération des données de FUL et IAE pour constituer les questionnaires
- Production de fichier de personnalisation pour COLTRANE
- Intégration des réponses sur COLTRANE
- Controle et Redressement à l'aide d'une module LSE (Langage de Spécification d'Ésane)
- Versement dans la BEC : Base Elementaire de Calcul pour CALVADOS

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

---

## OASIS/c'est pas fini 

- Utilisation de WS : IGESA , WS calcul d'APE.
- Récupération des données Externes pour affichage dans Oasis
- Gestion de la confidentialité de ces données à garantir
- Utilisation des données externe dans d'autres applications (CALVADOS)


---

## CALVADOS

- CALcul et VALidation des DOnneeS
- 1 IHM, 33 Batchs
- Utlise les données validées de l'EAP 
- Traitement de la non-réponse (imputation)
- Utilisation de la BEC pour Agregation
- IHM pour validation des agrégats
- Première publication d'indicateur à Eurostat au 30 juin
- Utilisation d'une Base Elémentaire de Diffusion 



---

## ORESTE

- Gestion des restructurations
- 1 IHM, 1 batch
- échange avec CITRUS dans les 2 sens
- peu ou pas d'évolution
