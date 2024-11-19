# Exercice du Projet 4

Votre but est de coder une application en ligne nommée **“AzerType”**.  
L’objectif de cette application est d’apprendre à taper plus vite au clavier, en tapant le plus rapidement possible et dans un temps imparti des mots proposés par l’application.

Nous allons réaliser l’intégralité de ce projet ensemble. Voici une capture d’écran pour vous montrer un aperçu du projet finalisé :

![image](https://github.com/user-attachments/assets/96572c05-3fd8-4067-96d7-3145c880f9f0)

---

## Objectif

Dans cette deuxième partie du cours, vous allez rédiger un programme informatique qui répond à une logique de programmation : votre navigateur est capable de comprendre et d’interpréter ce programme.

Avant de rentrer dans les lignes de code, arrêtons-nous sur quelques notions clés pour mieux appréhender le concept de logique de programmation.

---

## Appréhendez la notion d’algorithme

En tant que développeur, vous rédigez du code dans le but de développer un programme informatique. Vous allez donc écrire, en JavaScript, un ensemble d’instructions et d’opérations qui seront exécutées par un ordinateur dans un but précis.  
Dans notre cas, nous souhaitons coder un algorithme capable de :  

- **proposer des mots à un utilisateur** ;  
- **vérifier que les mots entrés par l’utilisateur sont corrects**.  

---

### Un algorithme ? Mais qu’est-ce que c’est ?

Un algorithme est une façon de concevoir les étapes d’un code dans le but de résoudre un problème donné.

Dans notre cas, l’application **AzerType** va proposer des mots, et l’utilisateur devra taper ces mots correctement avec son clavier.  
Notre problème est donc le suivant : comment faire comprendre cela à l’ordinateur ?  

L’idéal serait de lui fournir une liste d’étapes pour lui expliquer, pas à pas, chaque instruction qu’il doit exécuter. Eh bien, un **algorithme**, c’est exactement ça !

---

### Exemple d'algorithme

Notre algorithme pourrait donc ressembler à cette suite d’étapes :

1. **L’application propose un mot.**  
2. **L’utilisateur tape ce mot au clavier.**  
3. **Si le mot de l’utilisateur est exactement le même que le mot de l’application, alors on ajoute un point au score.**  
4. **On passe au mot suivant.**  
5. **On recommence à l’étape 1, jusqu’à ce que le temps soit écoulé.**  
