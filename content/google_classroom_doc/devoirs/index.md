---
date: 2016-06-25T12:21:48+02:00
title: Les Devoirs
weight: 40
---

{{< note title="Use Case" >}}
Je suis professeur de mathématiques. J'ai créé un devoir pour évaluer mes élèves en statistiques.

![Devoir Sujet](../images/classroomdoc_devoir_sujet.png)

Comment envoyer ce devoir aux élèves afin qu'ils puissent le faire dans la classe virtuelle ?
{{< /note >}}

## Créer un devoir
 Je dois commencer par créer un devoir. Pour cela, je clique sur le bouton marqué d'un signe <img src="../icons/plus.png" alt="plus" style="width: 20px;"/> en bas à droite et je choisis *Élaborer un devoir*.

![Devoir Sujet](../images/classroomdoc_devoir_creation.png)

Une fenêtre apparait dans laquelle je vais donner les instructions pour le devoir.

### Instructions du devoir
 Je commence par donner un titre à mon devoir. Ensuite je rédige les instructions. Généralement, mes instructions sont sur un document séparé. Je vais donc chercher le document sur Google Drive en cliquant sur l'icône <img src="../icons/google-drive.png" alt="google-drive" style="width: 20px;"/>. Je retrouve mon devoir dans la fenêtre qui apparait.

 ![Devoir Fenetre Drive](../images/classroomdoc_devoir_fenetre_drive.png)

 Je décide à présent d'une date de remise du devoir<sup id="note1">[1](#f1)</sup> (je pourrais aussi régler l'heure).

 ![Devoir Choix Date](../images/classroomdoc_devoir_date.png)

 Ensuite, pour ce devoir, je souhaite que les élèves rédigent directement leurs réponses sur le sujet. Ils doivent donc avoir chacun leur propre copie du document (un peu comme des photocopies qu'on distriburait en classe réelle). Je choisis donc *Faire une copie par élève* dans le menu déroulant de droite :

 ![Devoir Copie eleve](../images/classroomdoc_devoir_une_copie_par_eleve.png)



Une fois tout cela terminé, je peux publier mon devoir. Je clique sur le bouton *Créer un devoir*. Mon devoir apparait dans mon flux :

![Devoir Publiée Prof](../images/classroomdoc_devoir_publiee_prof.png)


## Côté élève

Aussitôt le devoir créé, les élèves reçoivent une notification par email :

![Devoir Notification Eleve](../images/classroomdoc_devoir_notif_eleve.png)

Un événement est automatiquement créé dans leur agenda :

![Devoir Agenda](../images/classroomdoc_devoir_notif_agenda.png)

Depuis ces deux endroits, mais aussi évidemment depuis le flux associé au cours, les élèves accèdent à leur devoir.

![Devoir Publication ELeve](../images/classroomdoc_devoir_publiee_eleve.png)

### Faire le devoir

Pour pouvoir faire leur devoir, l'élève doit cliquer sur le bouton *Ouvrir*.
(Dans son interface, le professeur voit que l'élève a commencé son devoir.)

![Devoir Ouvert](../images/classroomdoc_devoir_ouvert.png)

On peut voir qu'il peut ouvrir le sujet<sup id="note2">[2](#f2)</sup> mais aussi ajouter une pièce jointe ou créer un document Google.

Tout le temps de sa rédaction, l'élève peut recevoir des commentaires du professeur sur son devoir (annotation à côté de certains paragraphes) :

![Devoir Commentaire Eleve](../images/classroomdoc_devoir_commentaire_eleve.png)


Une fois que son devoir sera terminé, il cliquera sur le bouton *Rendre le devoir*. Lorsque ce bouton est pressé, plus de retour en arrière possible : l'élève ne peut plus modifier son document, seul le professeur le peut.


## Gérer les devoirs

Je clique sur le menu Devoir ![Devoir Menu](../images/classroomdoc_cours_menu1.png) en haut à gauche de l'interface et je choisis *Devoirs*.

![Devoir Menu](../images/classroomdoc_devoir_menu.png)


J'accède ainsi à la liste de tous les devoirs dans tous les cours. Le dernier devoir créé apparait en haut de la liste :

![Devoir Liste](../images/classroomdoc_devoir_liste.png)

En cliquant sur le titre de ce devoir, j'accède à la liste de tous les élèves. Je sais exactement qui a fait le devoir, qui est en train de le faire et qui ne l'a pas encore regardé.

![Devoir Rendre](../images/classroomdoc_devoir_rendre.png)

### Suivi des devoirs

Pendant que les élèves font leur travail, je peux accéder à leur copie, voir l'avancement des travaux... Je clique sur le devoir d'un élève qui s'ouvre. Je peux lui mettre des annotations directement sur sa copie par exemple.

![Devoir Ouvert](../images/classroomdoc_devoir_commentaire.png)

### Noter les devoirs

Lorsque le devoir est rendu par l'élève, il est temps de le noter ! Je peux décider de la note (par défaut sur 100 points).

![Devoir Changer Note](../images/classroomdoc_devoir_note_changer.png)

Je saisie la note dans le champs à côté du nom de l'élève dans la liste de gauche. Lorsque la note est entrée, le nom de l'élève est sélectionné, prêt à rendre la copie. Si je corrige et note d'autres copies, le nom des élèves se sélectionne au fur et à mesure.

Lorsque je clique sur le bouton *Rendre* je peux joindre un commentaire particulier (si je rends une seule copie) ou général (si je rends toutes les copies en même temps).

![Devoir Rendre Commentaire](../images/classroomdoc_devoir_rendre_comment.png)

Une fois le devoir rendu, l'élève reçoit une notification par email avec sa note.

![Devoir Note Email](../images/classroomdoc_devoir_note_email.png)

L'élève peut à nouveau modifier son devoir pour le corriger par exemple...

## Récupérer les notes

En haut à droite de la liste des devoirs, si je clique sur l'engrenage ![cog](../icons/cog.png) et je choisis le type de fichier sous lequel je veux récupérer ma liste de notes (Google Sheet ou CSV)

![Question Note Tableau](../images/classroomdoc_question_notes_tableau.png)

---------
**NOTES**

<b id="f1">1.</b> Décider de la date de remise n'implique pas que les élèves ne pourront pas le remettre hors délais. Leur devoir aura juste la mention *En retard*. [↩](#note1)

<b id="f2">2.</b> Remarquez le nom bizzare du sujet : *Copie de [Template] Copie de ...*. C'est une bizarrerie du système. C'est moche et ce sera sans doute changé dans les prochaines versions de Google Classroom. [↩](#note2)
