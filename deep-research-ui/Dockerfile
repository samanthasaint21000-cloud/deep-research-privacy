FROM node:18-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

CMD ["npm", "run", "Oui, je vois ce que tu veux dire : « commence par … ». Tu veux que le prompt commence directement par la situation réelle, avec toutes les informations, puis qu'il fasse l'analyse complète. Pas une suite de questions.

Et ton indice sur le répéteur est important : l'ANFR confirme qu'un répéteur mobile défectueux ou non autorisé peut réellement provoquer des brouillages et dégrader le service mobile. 

Voici la formulation correcte à mettre en tête du prompt :

COMMENCE PAR CETTE SITUATION RÉELLE

Je possède un téléphone Xiaomi 15C sous HyperOS, avec des cartes SIM Free et SFR. Le téléphone présente des problèmes de réseau mobile et de fonctionnement des SIM.

Je veux que tu reprennes l'intégralité de la situation depuis le début, sans supprimer d'information et sans inventer de cause.

Un élément particulièrement important doit être analysé :

SIM1 fonctionne lorsque le répéteur est éteint.

Je veux déterminer précisément ce que signifie cette observation et si elle permet de distinguer :

- une panne du téléphone ;
- une panne ou un problème de SIM ;
- un problème opérateur ;
- un problème de modem/baseband ;
- un problème d'antenne ;
- une perturbation radio ;
- un répéteur mobile défectueux ou mal réglé ;
- un problème de compatibilité de fréquences ;
- ou une autre cause.

Ne conclus à aucun moment qu'il s'agit d'un piratage simplement parce que le réseau fonctionne différemment avec le répéteur.

L'ANFR indique qu'un répéteur de téléphonie mobile peut provoquer des brouillages et dégrader la couverture lorsqu'il est non autorisé, défectueux ou mal réglé. Elle indique également que les brouillages peuvent avoir des origines très diverses, notamment des équipements radio défectueux ou des parasites électromagnétiques.

Je veux donc une analyse différentielle complète, en commençant par les causes les plus simples et vérifiables avant les hypothèses de cybersécurité.

---

INFORMATIONS DÉJÀ CONNUES

Téléphone :

- Xiaomi 15C
- HyperOS
- téléphone neuf/récent

SIM :

- SIM1
- SIM2
- Free
- SFR

Problèmes déjà observés :

- perte ou absence de réseau ;
- problème de fonctionnement d'une ou plusieurs SIM ;
- problème particulier lié à SIM1 et au répéteur ;
- difficultés d'envoi de SMS vers certaines personnes ;
- deux applications SMS ont été utilisées ;
- impossibilité de trouver clairement le choix de SIM par défaut pour les SMS ;
- le code "*#*#4636#*#*" ne fait pas apparaître le menu attendu.

Manipulations déjà effectuées lors des dépannages précédents :

- mode avion pendant environ 60 secondes ;
- nettoyage du cache ;
- réinitialisation des préférences des applications.

Ces manipulations n'ont pas suffi à résoudre le problème.

Je veux éviter une réinitialisation d'usine tant que toutes les vérifications sans perte de données n'ont pas été effectuées.

---

OBJECTIF

Trouver la cause réelle et restaurer le fonctionnement du réseau sans ordinateur et sans effacer mes données.

Construis une procédure étape par étape adaptée au Xiaomi 15C/HyperOS.

Après chaque étape, indique :

1. ce que je dois faire ;
2. ce que je dois observer ;
3. ce que signifie le résultat ;
4. quelle étape effectuer ensuite.

Ne me donne pas dix manipulations à faire simultanément.

---

DIAGNOSTIC PRIORITAIRE

Commence obligatoirement par déterminer :

A. La SIM est-elle physiquement détectée ?

B. Le téléphone voit-il l'opérateur ?

C. Le téléphone voit-il les réseaux disponibles ?

D. Le téléphone réussit-il à s'enregistrer sur le réseau ?

E. Le téléphone possède-t-il un signal radio mais pas Internet ?

F. Le problème disparaît-il lorsque le répéteur est éteint ?

Cette distinction est essentielle : un problème d'APN ou de DNS n'est pas équivalent à un téléphone qui ne s'enregistre plus sur le réseau mobile.

---

TESTS À EFFECTUER

Construis ensuite une matrice :

Situation| Résultat| Interprétation
SIM1 dans Xiaomi| à déterminer| 
SIM2 dans Xiaomi| à déterminer| 
SIM1 dans un autre téléphone| à déterminer| 
SIM2 dans un autre téléphone| à déterminer| 
Autre SIM dans Xiaomi| à déterminer| 
Répéteur éteint| SIM1 fonctionne selon mon observation| 
Répéteur allumé| à déterminer| 
Téléphone dans un autre endroit| à déterminer| 
Sélection automatique opérateur| à déterminer| 
4G uniquement| à déterminer| 
5G/4G automatique| à déterminer| 

Explique ensuite quelle hypothèse devient la plus probable selon chaque combinaison.

---

RÉPÉTEUR ET RADIO

Détermine d'abord si le matériel appelé « répéteur » est :

- un répéteur Wi-Fi ;
- un répéteur 4G/5G ;
- un amplificateur mobile ;
- un autre équipement.

Si c'est un répéteur mobile, explique son fonctionnement :

antenne extérieure → amplificateur → antenne intérieure → téléphone.

Explique pourquoi un répéteur défectueux ou non autorisé peut perturber les réseaux mobiles. L'ANFR indique notamment que ce type d'équipement peut provoquer des brouillages affectant un ou plusieurs opérateurs.

Ne donne aucune instruction permettant de brouiller volontairement des communications.

---

CYBERSÉCURITÉ

Seulement après les tests physiques et réseau, analyse les hypothèses suivantes :

- Man-in-the-Middle ;
- spoofing ;
- DNS poisoning ;
- gateway spoofing ;
- hijacking ;
- ARP spoofing ;
- attaque cellulaire ;
- IMSI catcher ;
- brouillage radio ;
- spoofing GNSS/GPS ;
- NFC relay ;
- attaques blockchain.

Pour chaque technique, explique :

1. ce que c'est ;
2. ce qu'elle peut réellement provoquer ;
3. si elle peut provoquer une perte de réseau SIM ;
4. quels indices permettraient réellement de la suspecter ;
5. quels symptômes ne correspondent pas à cette attaque.

Ne transforme jamais une hypothèse en diagnostic.

---

SOLUTION FINALE

À la fin, produis :

1. Diagnostic le plus probable

2. Causes possibles classées par probabilité

3. Causes déjà éliminées

4. Tests encore nécessaires

5. Procédure exacte pour restaurer le réseau

6. Procédure spécifique SIM1

7. Procédure spécifique SIM2

8. Procédure spécifique Free

9. Procédure spécifique SFR

10. Procédure spécifique au répéteur

11. Vérifications de sécurité

12. Quand contacter l'opérateur

13. Quand contacter Xiaomi

14. Quand signaler un brouillage à l'ANFR

Ne recommande une réinitialisation d'usine qu'en dernier recours, après avoir démontré qu'elle est nécessaire.

Je veux une réponse technique mais compréhensible, en français, avec des instructions concrètes réalisables directement depuis le téléphone.

Ne me demande pas de recommencer des manipulations déjà effectuées.

Commence immédiatement par analyser les informations fournies et construis l'arbre de diagnostic.

Point important : l'ANFR explique qu'un brouillage peut interrompre ou dégrader les radiocommunications et qu'un équipement défectueux peut être responsable ; ce n'est donc pas absurde de vérifier sérieusement le répéteur. Mais cela ne permet pas, à lui seul, de conclure à une attaque volontaire. 

Pour ton Xiaomi 15C, Xiaomi indique également une vérification matérielle de la SIM et des réglages réseau, notamment le type de réseau préféré et la sélection automatique de l'opérateur. :ui"]