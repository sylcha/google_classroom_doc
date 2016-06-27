---
date: 2016-06-25T12:20:23+02:00
title: Créer une classe virtuelle
weight: 10
---
 Pour créer un classe virtuelle, je clique sur le signe <img src="../icons/plus.png" alt="plus" style="width: 20px;"/> en haut à droite à côté de mon adresse email.

 ![Signe Plus](../images/classroomdoc_plus.png)

 Je choisis alors l'option *Créer un cours* dans le menu déroulant.

 ![Cours Création](../images/classroomdoc_cours_creation.png)


## Décider d'un nom

Une fois que j'ai cliqué sur *Créer un cours*, je dois nommer ce cours :

![Cours Nommer](../images/classroomdoc_cours_nommer.png)

Le choix du nom est important car il va décider du label du dossier dans Google Drive (voir [plus loin](#nom_dossier)). Il est crucial que tous les enseignants utilisent la même norme pour nommer ces cours afin que les élèves ne soient pas perdus.

### Norme générale

J'utilise la norme suivante :

```
Nom du cours : <matiere>-<sous_matiere>
Section : <niveau><section>
```
{{< note title="Use Case" >}}
Je suis professeur de mathématiques. Je souhaite créer un espace de travail spécifique pour mon groupe d'AP de 6e B. Ainsi, mon cours s'intitulera :

```
Nom du cours : Maths-AP
Section : 6B
```
{{< /note >}}

j'arrive alors sur le mur de la classe : c'est ici que tout se passe, dans une seule page.

![Cours Mur](../images/classroomdoc_cours_premiere.png)

## Symbiose avec le Drive

Le plus gros avantage à utiliser Google Classroom réside dans son intégration parfaite avec le système Google.

### Création d'un dossier sur le Drive<a name="nom_dossier"></a>

À peine le cours créé, j'ai un dossier `Classroom` dans le Drive associé à mon adresse du LFV. Dans ce dossier, il y a un sous-dossier au nom du cours créé.

![Cours Drive](../images/classroomdoc_cours_drive.png)

Tous les documents que je partage avec les élèves iront dans ce dossiers et ne seront visibles que par eux. En effet, lorsque un élève rejoint le cours, il se passe la même chose pour lui : un dossier `Classroom` est créé avec un sous-dossier au nom du cours.

### Création d'un agenda

Avec le dossier dans le Drive, google crée aussi un agenda spécifique pour le cours. À chaque fois que je donnerai un devoir aux élèves, un événement sera créé dans cet agenda.

![Cours Agenda](../images/classroomdoc_cours_agenda.png)

## Description de l'interface

### Les onglets

Trois onglets avec trois buts différents :

![Cours Onglets](../images/classroomdoc_cours_onglets.png)

1. Le **Flux** : toutes les informations publiées sur le site sont ici, empilées de la plus ancienne à la plus récente (la dernière publication étant la première dans la liste)

2. Les **Élèves** : la liste de tous les élèves inscrits dans ce cours.

3. **À propos** : des réglages et des informations additionnelles peuvent être ajoutées ici.

### Réglages de l'apparence

Sur la droite de la fenêtre, juste en dessous de l'adresse email, j'ai accès aux réglages du thème du cours : c'est là que je peux décider de la couleur, de la photo, etc. et personnaliser un peu mon cours. C'est important car sinon les élèves auront du mal à faire la différence avec les cours des autres professeurs.

![Cours Themes](../images/classroomdoc_cours_theme.png)

### Menu général

En haut à gauche de l'interface, j'ai un bouton ![Cours Menu1](../images/classroomdoc_cours_menu1.png) qui permet de déployer un menu.

<!---
![Cours Menu1](../images/classroomdoc_cours_menu2.png)
-->

Ce menu permet de naviguer facilement entre tous les cours, devoirs et aussi d'accéder aux paramètres.

### Ajouter du contenu

Enfin, sur la partie inférieure droite, on aperçoit un gros bouton marqué d'un <img src="../icons/plus.png" alt="plus" style="width: 20px;"/>. En cliquant sur ce bouton, j'accède au menu des contenus.

![Cours Menu Contenu](../images/classroomdoc_cours_ajouter_contenu.png)


## Comment rejoindre une classe ?

### Les élèves s'inscrivent tous seuls

C'est la solution la plus confortable pour l'enseignant. Je donne le code de mon cours aux élèves que je souhaite inscrire. Je trouve ce code sur la droite de la partie *Flux*

![Cours Code](../images/classroomdoc_cours_code.png)

De leur côté, les élèves cliquent sur le img src="../icons/plus.png" alt="plus" style="width: 20px;"/> à côté de leur adresse email (en haut à droite) et choisissent l'option *Se connecter à un cours*. Ils doivent saisir le code dans cette fenêtre

![Cours Code](../images/classroomdoc_cours_rejoindre.png)

### Inviter des élèves

Ici, c'est l'enseignant qui invite les élèves à participer au cours. Pas besoin de code. Je clique sur l'onglet *Élèves*. J'accède alors à cette partie du cours :

![Cours Inviter1](../images/classroomdoc_cours_inviter1.png)

En cliquant sur le bouton *Inviter*, une fenêtre s'ouvre où je peux choisir les adresses des élèves.

![Cours Inviter2](../images/classroomdoc_cours_inviter2.png)

Seuls les élèves ayant une adresse `*@lfv.pl` pourront être inviter à rejoindre la classe.

1. Je tape le nom de l'élève dans le champ de recherche.
2. Je coche la case correspondant à l'adresse.
3. Je recommence avec un autre nom.
4. Une fois fini, je clique sur le bouton *Inviter les élèves*.

Les élèves reçoivent alors un email d'invitation. Ils devront valider leur inscription au cours en cliquant sur le lien dans cet email.

{{< note title="Adresses des élèves" >}}
Je ne peux pas faire de saisie d'adresse mais seulement choisir une adresse parmie une liste. C'est **très** contraignant (il faut chercher les adresses une à une) mais cela permet à Google de s'assurer que les utilisateurs invités restent dans le giron des adresses du LFV.

Personnellement, j'utilise la formule précédente où chaque élève s'inscrit.
{{< /note >}}

## Comment collaborer à un cours ?

Il peut y avoir plusieurs enseignants qui participent ensemble à l'élaboration d'un cours (TPE, enseignement d'exploration en seconde, etc.). Le service Google Classroom permet de gérer cela. Moi qui ai créé le cours, je clique sur l'onglet *À propos*. J'accède alors à un bouton *Inviter un enseignant*.

![Cours Inviter Prof](../images/classroomdoc_cours_inviter_prof.png)

L'enseignant invité aura bien évidemment le droit de publier dans mon cours.
