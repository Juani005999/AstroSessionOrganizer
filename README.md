# AstroSessionOrganizer
***AstroSessionOrganizer*** (**ASO**) est un utilitaire (freeware) sous ***Windows*** permettant la gestion et la sauvegarde des sessions d'observations astro-photographiques et des données associées.

![AstroSessionOrganizer](images/ASO.png)

## Sommaire
- [Affichage](#affichage)
    - [Menu](#menu)
        - [Menu Fichier](#menu-fichier)
        - [Menu Outils](#menu-outils)
            - [Options](#boîte-de-dialogue-options)
        - [Menu ?](#menu-)
           - [A Propos](#boîte-de-dialogue-a-propos)
    - [Barre d'outils](#barre-doutils)
    - [Onglets](#onglets)
        - [Onglet Sessions d'observations](#onglet-sessions-dobservations)
            - [Panneau détail d'une session d'observation](#panneau-détail-dune-session-dobservations)
            - [Boîte de dialogue Création d'un Exif](#boîte-de-dialogue-création-dun-exif)
        - [Onglet Catalogue des objets célestes](#onglet-catalogue-des-objets-célestes)
            - [Zone de filtres des objets célestes affichés](#zone-de-filtres-des-objets-célestes-affichés)
            - [Panneau détail d'un objet céleste](#panneau-détail-dun-objet-céleste)
        - [Onglet Equipements et sites d'observations](#onglet-equipements-et-sites-dobservations)
            - [Panneau propriétés d'un site ou d'un équipement](#panneau-propriétés-dun-site-ou-dun-équipement)
                - [Propriétés d'un site d'observations](#propriétés-dun-site-dobservations)
                - [Propriétés d'un setup](#propriétés-dun-setup)
                - [Propriétés d'une lunette / téléscope](#propriétés-dune-lunette--téléscope)
                - [Propriétés d'une monture](#propriétés-dune-monture)
                - [Propriétés d'une caméra](#propriétés-dune-caméra)
                - [Propriétés d'un filtre](#propriétés-dun-filtre)
                - [Propriétés d'un équipement divers](#propriétés-dun-équipement-divers)
                - [Propriétés d'un logiciel](#propriétés-dun-logiciel)
    - [Barre de statut](#barre-de-statut)
        - [Barre de statut de l'onglet Sessions d'observations](#barre-de-statut-de-longlet-sessions-dobservations)
        - [Barre de statut de l'onglet Catalogue des objets célestes](#barre-de-statut-de-longlet-catalogue-des-objets-célestes)
        - [Barre de statut de l'onglet Equipements et sites d'observations](#barre-de-statut-de-longlet-equipements-et-sites-dobservations)
- [Saisie](#saisie)
    - [Session d'observations](#session-dobservations)
        - [Ajout, modification, suppression d'une session d'observations](#ajout-modification-suppression-dune-session-dobservations)
        - [Sélection d'un objet céleste](#sélection-dun-objet-céleste)
            - [Boîte de dialogue de sélection d'un objet céleste](#boîte-de-dialogue-de-sélection-dun-objet-céleste)
        - [Date de la session d'observations](#date-de-la-session-dobservations)
        - [Sélection du site d'observations](#sélection-du-site-dobservations)
        - [Sélection du répertoire contenant les images de la session](#sélection-du-répertoire-contenant-les-images-de-la-session)
        - [Commentaires d'une session](#commentaires-dune-session)

## Affichage
**ASO** est composé d'un menu, d'une barre d'outil, de trois onglets de visualisations, et d'une barre de statut.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

### Menu
![Menu](images/Affichage_Menu.png)

Le menu est constitué des éléments suivants :
- Fichier
- Outils
- ?

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

#### Menu 'Fichier'
![Menu Fichier](images/Menu_Fichier.png)

Le menu 'Fichier' contient les éléments suivants :
- Sauvegarder la base de données\
Cette action permet de sauvegarder la base de données de **ASO**.

> [!WARNING]
> La sauvegarde de la base de données **ne comprend pas** les images. La base de données contient les informations de sessions, des objets célestes, des équipements et sites d'observations.

- Quitter\
Permet de quitter l'application **ASO**.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

#### Menu 'Outils'
![Menu Fichier](images/Menu_Outil.png)

Le menu 'Fichier' contient l'élément suivant :
- Options\
Cette action permet d'ouvrir la boîte de dialogue ***Options***.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

##### Boîte de dialogue 'Options'
![Menu Fichier](images/BoiteDeDialogue_Options.png)

Cette boîte de dialogue permet de définir les options de communication avec les logiciels ***Stellarium*** et ***Cartes du Ciel***.\
Les Options par défaut sont :
- ***Stellarium*** :
    - Serveur   : **localhost**
    - Port      : **8090**
- ***Cartes du Ciel*** :
    - Serveur   : **127.0.0.1**

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

#### Menu '?'
![Menu ?](images/Menu_APropos.png)

Le menu '?' contient l'élément suivant :
- A Propos\
Cette action permet d'ouvrir la boîte de dialogue ***A Propos***.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

##### Boîte de dialogue 'A Propos'
![Menu Fichier](images/BoiteDeDialogue_APropos.png)

Cette boîte de dialogue permet d'afficher les informations à propos du logiciel ***AstroSessionOrganizer*** (***ASO***).\
Il est également possible via le bouton présent d'ouvrir les fichiers de log de l'application.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

### Barre d'outils
![Barre d'outils](images/Affichage_BarreDOutils.png)

La barre d'outils comprend les raccourcis vers les actions suivantes :
- Nouvelle session d'observations
- Nouvel objet céleste
- Nouveau site d'observations
- Nouveau Setup
- Nouvel équipement
- Nouveau logiciel
- Modifier l'élément sélectionné
- Supprimer l'élément sélectionné
- Raccourci vers l'application ***AstroTargetSelector*** (***ATS***)

> [!NOTE]
> Le détail des actions ci-dessus est décrite dans la partie ***[Saisie](#saisie)***.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

### Onglets
![Onglets](images/Affichage_Onglets.png)

Cette partie comprend l'affichage des onglets suivants :
- Sessions d'observations.
- Catalogue des objets célestes.
- Equipements et sites d'observations.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

#### Onglet Sessions d'observations
![Onglet Session d'observations](images/Onglet_Sessions.png)

Cet onglet permet d'afficher la liste des sessions d'observations enregistrées.\
L'affichage de cet onglet est divisé en trois parties :
- Une liste arborescente comprenant les éléments :
    - ***Date***\
    Cet élément contient toutes les années/mois correspondant aux sessions présentes dans la base de données.
    - ***Constellations***\
    Cet élément contient la liste des constellations correspondant aux sessions présentes dans la base de données.
    - ***Type d'objets célestes***\
    Cet élément contient la liste des type d'objets célestes correspondant aux sessions présentes dans la base de données.
- Une liste principale contenant la liste des sessions en fonction de l'élément sélectionné dans la liste arborescente.
- Un panneau permettant d'afficher le détail d'une session sélectionnée.

> [!TIP]
> La liste des sessions peut être triée par ordre croissant ou décroissant en cliquant sur une en-tête de colonne de la liste.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

##### Panneau détail d'une Session d'observations
![Détail d'une session d'observation](images/Panneau_DetailSession.png)

Lorsqu'une session d'observation est sélectionnée dans la liste, le panneau de détail de la session apparait.\
Ce panneau permet l'affichage des différentes informations concernant la session sélectionnée, et la possibilité d'effectuer des actions supplémentaires sur cette session.

Informations affichées :
- Informations de l'objet céleste concerné par la session :
    - Miniature de l'image finale.\
    Par défaut, l'image utilisée est la première du répertoire des images de la session.
    - Nom.
    - Type.
    - Dénominations secondaires.
    - Constellation.
    - Coordonnées en RA/DEC.
- Informations sur la session :
    - Date.
    - Temps total (calculée à partir des brutes ajoutés à la session).
    - Site d'observations.
    - Setup utilisé (si défini dans la session).
    - Commentaires.
    - Répertoire où se trouvent les images de la session.
    - Liste de équipements utilisés.
    - Liste des logiciels utilisés pour le traitement.
    - Liste des observations (brutes, darks, ...).

Actions possibles :
- En cliquant sur la miniature de la session, celà permet l'affichage de l'image dans une nouvelle fenêtre.
- L'icone ![Loupe](images/Bouton_Loupe.png) est un raccourci permettant d'afficher l'objet céleste concerné directement dans l'onglet ***[Catalogue des objets célestes](#onglet-catalogue-des-objets-célestes)***.
- L'icone ![Nouvelle miniature](images/Bouton_NewThumbnail.png) permet de modifier l'image de la session affichée dans la miniature.
- Lorsqu'une image pour la miniature de la session a été sélectionnée, l'icone ![Supprimer miniature](images/Bouton_DeleteThumbnail.png) permet de supprimer cette sélection. L'image utilisée redevient l'image par défaut.\
Lorsqu'aucune image n'a été sélectionnée, ce bouton est grisé.
- L'icone ![ASTAP](images/Bouton_Astap.png) permet de lancer le logiciel ***ASTAP*** pour faire de l'astrométrie sur l'image de la session.\
Lors du clic sur ce bouton, une boîte de dialogue apparait permettant la sélection de l'image a envoyer dans l'astrométrie ***ASTAP***. Par défaut, le répertoire sélectionné pour la sélection de l'image est le répertoire des images saisi pour la session.\
Si le logiciel ***ASTAP*** n'est pas installé sur l'ordinateur, ce bouton est grisé.
- L'icone ![AstroTargetSelector](images/Bouton_ATS.png) permet de visualiser l'objet de la session dans le logiciel ***AstroTargetSelector***.\
Lors du clic sur ce bouton, le logiciel ***AstroTargetSelecor*** s'ouvre avec l'objet de la session présélectionné.\
Si le logiciel ***AstroTargetSelector*** n'est pas installé sur l'ordinateur, ce bouton est grisé.
- L'icone ![Cartes du Ciel](images/Bouton_CDC.png) permet de visualiser l'objet de la session dans le logiciel ***Cartes du Ciel***.\
Lors du clic sur ce bouton, le logiciel ***Cartes du Ciel*** s'ouvre avec l'objet de la session présélectionné.\
Si le logiciel ***Cartes du Ciel*** n'est pas installé sur l'ordinateur, ce bouton est grisé.
- L'icone ![Stellarium](images/Bouton_Stellarium.png) permet de visualiser l'objet de la session dans le logiciel ***Stellarium***.\
Lors du clic sur ce bouton, le logiciel ***Stellarium*** s'ouvre avec l'objet de la session présélectionné.\
Si le logiciel ***Stellarium*** n'est pas installé sur l'ordinateur, ce bouton est grisé.
- L'icone ![Images](images/Bouton_Images.png) permet d'ouvrir le répertoire des images de la session.\
Ce répertoire est défini dans les paramètres de la session (Cf. partie Saisie d'une session).
- L'icone ![Exif](images/Bouton_Exif.png) permet d'ouvrir la boîte de dialogue permettant la création d'un Exif pour la session (Cf. partie [Boîte de dialogue Création d'un Exif de session](#boîte-de-dialogue-création-dun-exif)).

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

##### Boîte de dialogue Création d'un Exif
![Création d'un Exif](images/BoiteDeDialogue_Exif.png)
![Exif](images/Exif_Resultat.png)

Cette boîte de dialogue permet la création d'un Exif pour la session d'observations.\
Elle contient une zone de paramètres, et une zone de rendu.

La zone de paramètres contient les éléments suivants :
- ***Afficher le lieu*** : affiche les coordonnées GPS du site d'observations.
- ***Afficher les commentaires*** : affiche les commentaires de la session. Si aucun commentaire n'a été saisi pour la session, cette zone est grisée.
- ***Afficher les dénominations*** : affiche les dénominations secondaires de l'objet céleste.
- ***Afficher les observations*** : affiche la liste des observations pour la session.
- ***Afficher l'image de l'objet à la création (Haut / Bas)*** : ajoute, lors de la création de l'exif, l'image de la session, soit au-dessous, soit en dessous des données de l'Exif.

La zone de droite des données de l'Exif permet d'afficher au choix quatre images :
- ***Afficher l'image de l'objet*** : affiche une miniature de l'image de la session.
- ***Afficher l'image de la constellation*** : affiche une miniature de la constellation de l'objet céleste.
- ***Afficher l'image du setup*** : affiche l'image du setup sélectionné pour cette session.
- ***Afficher l'image du site*** : Affiche l'image du site d'observation.

> [!TIP]
> Il est possible de modifier l'apparence des données Exif en modifiant chaque zone.\
En passant le curseur de la souris sur les ***barres grises***, vous avez la possibilité de cliquer/déplacer afin de modifier les dimensions de chaque zone.\
Modifier les dimensions de la fenêtre, notament la hauteur, permet également d'ajuster le rendu final de l'Exif.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

#### Onglet Catalogue des objets célestes
![Onglet Catalogue des objets célestes](images/Onglet_Catalogue.png)

Cet onglet permet d'afficher la liste des objets célestes du catalogue.\
L'affichage de cet onglet est divisé en quatre parties :
- Une liste arborescente comprenant les éléments :
    - ***Déjà observés***\
    Cet élément contient toutes les années/mois correspondant aux objets du catalogue déjà observés.
    - ***Constellations***\
    Cet élément contient la liste des constellations de tous les objets du catalogue.
    - ***Type d'objets célestes***\
    Cet élément contient la liste des type d'objets célestes de tous les objets du catalogue.
- Une [zone de recherche](#zone-de-filtre-des-objets-célestes-affichés) permettant de filtrer la liste des objets célestes.
- Une liste principale contenant la liste des objets célestes en fonction de l'élément sélectionné dans la liste arborescente et du filtre appliqué.
- Un panneau permettant d'afficher le détail de l'objet céleste sélectionné.

> [!TIP]
> La liste des objets célestes peut être triée par ordre croissant ou décroissant en cliquant sur une en-tête de colonne de la liste.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

##### Zone de filtres des objets célestes affichés
![Zone de filtres des objets célestes affichés](images/ZoneFiltre_ObjetsCelestes.png)

La zone de recherche permettant de filtrer la liste des objets célestes comprend les filtres suivants :
- ***Rechercher dans la liste*** : permet de rechercher sur le nom et/ou les dénominations.
- ***Type*** : permet de filtrer la liste en fonction du type d'objet céleste.
- ***Catalogue*** : permet de filtrer sur un catalogue (Messier, NGC, ...).

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

##### Panneau détail d'un objet céleste
![Détail d'un objet céleste](images/Panneau_DetailObjet.png)

Lorsqu'un objet céleste est sélectionné dans la liste, le panneau de détail de l objet apparait.\
Ce panneau permet l'affichage des différentes informations concernant l'objet céleste et des sessions d'observations associées, et la possibilité d'effectuer des actions supplémentaires.

Informations affichées :
- Informations de l'objet céleste :
    - Miniature de la constellation de l'objet.
    - Nom.
    - Type.
    - Dénominations secondaires.
    - Constellation.
    - Coordonnées en RA/DEC.
    - Catalogue.
    - Magnitude.
    - Magnitude (BMag).
    - Grandeur maximum.
    - Grandeur minimum.
    - Redshift (décalage au rouge).
    - Distance (KPc).
    - Liste des sessions d'observations sur l'objet céleste.
    - Miniature de la session sélectionnée dans la liste des sessions liées à l'objet.


Actions possibles :
- En cliquant sur la miniature de la constellation, celà permet l'affichage de l'image dans une nouvelle fenêtre.
- En cliquant sur la miniature de la session sélectionnée, celà permet l'affichage de l'image dans une nouvelle fenêtre.
- L'icone ![Loupe](images/Bouton_Loupe.png) est un raccourci permettant d'afficher la session d'observations concernée directement dans l'onglet ***[Sessions d'observations](#onglet-sessions-dobservations)***.
- L'icone ![AstroTargetSelector](images/Bouton_ATS.png) permet de visualiser l'objet céleste dans le logiciel ***AstroTargetSelector***.\
Lors du clic sur ce bouton, le logiciel ***AstroTargetSelecor*** s'ouvre avec l'objet céleste présélectionné.\
Si le logiciel ***AstroTargetSelector*** n'est pas installé sur l'ordinateur, ce bouton est grisé.
- L'icone ![Cartes du Ciel](images/Bouton_CDC.png) permet de visualiser l'objet céleste dans le logiciel ***Cartes du Ciel***.\
Lors du clic sur ce bouton, le logiciel ***Cartes du Ciel*** s'ouvre avec l'objet céleste présélectionné.\
Si le logiciel ***Cartes du Ciel*** n'est pas installé sur l'ordinateur, ce bouton est grisé.
- L'icone ![Stellarium](images/Bouton_Stellarium.png) permet de visualiser l'objet céleste dans le logiciel ***Stellarium***.\
Lors du clic sur ce bouton, le logiciel ***Stellarium*** s'ouvre avec l'objet céleste présélectionné.\
Si le logiciel ***Stellarium*** n'est pas installé sur l'ordinateur, ce bouton est grisé.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

#### Onglet Equipements et sites d'observations
![Onglet Equipements et sites d'observations](images/Onglet_Equipements.png)

Cet onglet permet l'affichage des sites d'observations et des équipements.\
L'affichage de cet onglet est divisé en deux parties :
- Une liste des sites d'observations et  équipements comprenant sept rubriques :
    - ***Sites*** : liste des sites d'observations.
    - ***Setup*** : liste des setup.
    - ***Lunettes et télescopes*** : liste des lunettes et télescopes.
    - ***Montures*** : liste des montures.
    - ***Caméras*** : liste des caméras et appareil photos.
    - ***Filtres*** : liste des filtres.
    - ***Divers*** : liste de matériels divers.
    - ***Logiciels*** : liste des logiciels nécessaire au traitement, à la gestion et à l'aquisition d'image.\
    Cette rubriques comprend trois catégories de logiciel :
        - ***Aquisition***.
        - ***Pré-Traitement***.
        - ***Traitement***.
        - ***Divers***.
- Un panneau permettant d'afficher les propriétés de l'élément sélectionné.

> [!TIP]
> La saisie de setup est optionnelle et permet de regrouper plusieurs équipements afin de faciliter la saisie d'une session d'observations.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

##### Panneau propriétés d'un site ou d'un équipement

Ce panneau permet d'afficher les propriétés de l'élément sélectionné dans la liste.

###### Propriétés d'un site d'observations
![Propriétés Sites](images/Propriétés_Site.png)

Ce panneau permet l'affichage des propriétés du site sélectionné, et permet également de positionner une image pour le site.

Informations affichées :
- Le Nom.
- Les coordonées GPS.
- L'indice de Bortle.
- La miniature de l'image du site.

> [!TIP]
> Un clic sur la miniature du site permet l'affichage de l'image dans une nouvelle fenêtre.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

###### Propriétés d'un setup
![Propriétés Setup](images/Propriétés_Setup.png)

Ce panneau permet l'affichage des propriétés du setup sélectionné, et permet également de positionner une image pour le setup.

Informations affichées :
- Le Nom.
- La liste des équipements constituant le setup.
- La miniature du setup.

> [!TIP]
> La saisie de setup est optionnelle et permet de regrouper plusieurs équipements afin de faciliter la saisie d'une session d'observations.\
La création d'un setup permet également l'affichage d'une miniature dans les Exifs.\
Un clic sur la miniature du setup permet l'affichage de l'image dans une nouvelle fenêtre.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

###### Propriétés d'une lunette / téléscope
![Propriétés d'une lunette / téléscope](images/Propriétés_Telescope.png)

Ce panneau permet l'affichage des propriétés de la lunette ou du téléscope sélectionné.

Informations affichées :
- Le Nom.
- Le type d'équipement.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

###### Propriétés d'une monture
![Propriétés d'une monture](images/Propriétés_Monture.png)

Ce panneau permet l'affichage des propriétés de la monture sélectionnée.

Informations affichées :
- Le Nom.
- Le type d'équipement.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

###### Propriétés d'une caméra
![Propriétés d'une caméra](images/Propriétés_Camera.png)

Ce panneau permet l'affichage des propriétés de la caméra sélectionnée.

Informations affichées :
- Le Nom.
- Le type d'équipement.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

###### Propriétés d'un filtre
![Propriétés d'un filtre](images/Propriétés_Filtre.png)

Ce panneau permet l'affichage des propriétés du filtre sélectionné.

Informations affichées :
- Le Nom.
- Le type d'équipement.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

###### Propriétés d'un équipement divers
![Propriétés d'un équipement divers](images/Propriétés_Divers.png)

Ce panneau permet l'affichage des propriétés de l'équipement sélectionné.

Informations affichées :
- Le Nom.
- Le type d'équipement.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

###### Propriétés d'un logiciel
![Propriétés d'un logiciel](images/Propriétés_Logiciel.png)

Ce panneau permet l'affichage des propriétés du logiciel sélectionné.

Informations affichées :
- Le Nom.
- Le type de logiciel.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

### Barre de statut
![Barre de statut](images/Affichage_BarreDeStatut.png)

La barre de statut affiche des informations supplémentaires en fonction de l'onglet affiché.

#### Barre de statut de l'onglet Sessions d'observations
![Barre de statut de l'onglet Sessions d'observations](images/Statut_Sessions.png)

Lorsque l'onglet [Session d'observations](#onglet-sessions-dobservations) est affiché, la barre de statut affiche :
- Le nombre total de sessions d'observations enregistrées.
- Le nombre de sessions d'observations affichées dans la liste des sessions.

> [!NOTE]
> Le nombre de sessions d'observations affichées dans la liste est dépendant de l'élément sélectionné dans la liste arborescente.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

#### Barre de statut de l'onglet Catalogue des objets célestes
![Barre de statut de l'onglet Catalogue des objets célestes](images/Statut_Objets.png)

Lorsque l'onglet [Catalogue des objets célestes](#onglet-catalogue-des-objets-célestes) est affiché, la barre de statut affiche :
- Le nombre total d'objets célestes répertoriés dans le catalogue.
- Le nombre d'objets célestes affichés dans la liste des objets.

> [!NOTE]
> Le nombre d'objets célestes affichés dans la liste est dépendant de l'élément sélectionné dans la liste arborescente, et des éléments positionnés dans la zone de filtre.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

#### Barre de statut de l'onglet Equipements et sites d'observations
![Barre de statut de l'onglet Equipements et sites d'observations](images/Statut_Equipements.png)

Lorsque l'onglet [Equipements et sites d'observations](#onglet-equipements-et-sites-dobservations) est affiché, la barre de statut affiche :
- Le nombre de sites d'observations enregistrés.
- Le nombre de setups enregistrés.
- Le nombre d'équipements enregistrés

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

## Saisie

### Session d'observations
![Edition d'une session d'observations](images/Session_New.png)

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

#### Ajout, modification, suppression d'une session d'observations

Pour ajouter, modifier ou supprimer une session d'observations, vous pouvez le faire :
- Depuis la barre d'outils :
    - Le bouton ![Nouvelle Session](images/ToolBar_NewSession.png) permet d'ouvrir la boîte de dialogue de création d'une nouvelle session.
    - Le bouton ![Modifier](images/ToolBar_EditSession.png) permet de modifier la session sélectionnée.\
    Si aucune session n'est sélectionnée, ce bouton est grisé.
    - Le bouton ![Supprimer](images/ToolBar_Delete.png) permet de supprimer la session sélectionnée.\
    Si aucune session n'est sélectionnée, ce bouton est grisé.

- Depuis le menu contextuel :\
![Menu contextuel](images/Session_ContextMenu_NewSession.png)\
En faisant un clic avec le bouton droit de la souris sur la liste des sessions d'observations, le menu contextuel apparait.\
Ce menu contextuel contient les éléments suivants :
    - ***Nouvelle session d'observations*** : permet d'ouvrir la boîte de dialogue de création d'une nouvelle session.
    - ***Modifier*** : permet de modifier la session sélectionnée.\
    Si aucune session n'est sélectionnée, ce menu est grisé.
    - ***Supprimer*** : permet de supprimer la session sélectionnée.\
    Si aucune session n'est sélectionnée, ce menu est grisé.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

#### Sélection d'un objet céleste

- La zone ci-dessous indique le nom de l'objet céleste actuellement sélectionné pour la session d'observations.\
![Nom de l'objet céleste](images/NewSession_SelectionObjet.png)
\
Le bouton ![Sélection de l'objet céleste](images/NewSession_Edit.png) permet d'ouvrir la [boîte de dialogue de sélection d'un objet céleste](#boîte-de-dialogue-de-sélection-dun-objet-céleste).


- La zone ci-dessous indique les informations complémentaires concernant l'objet céleste sélectionné.\
![Informations de l'objet céleste](images/NewSession_InformationObjet.png)\
Ces informations sont :
    - Type de l'objet.
    - Nom et abbréviation de la constellation.
    - Dénominations supplémentaires de l'objet.


<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

##### Boîte de dialogue de sélection d'un objet céleste
![Boîte de dialogue de sélection d'un objet céleste](images/BoiteDeDialogue_SelectionObjet.png)

Cette boîte de dialogue permet la sélection d'un objet céleste pour la session.\
Elle est composée de deux zones :
- ***Rechercher*** : zone de saisie permettant de saisir les éléments de recherche.
- ***Résultat de la recherche*** : résultat de la recherche dans le catalogue complet correspondant à la saisie.

> [!NOTE]
> Le résultat de la recherche s'actualise lors de la saisie dans la zone de recherche.\
Il est nécessaire de saisir au minimum trois caractères pour lancer la recherche.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

#### Date de la session d'observations
![Date de la session d'observations](images/Session_Date.png)

Ce champ permet de sélectionner la date de la session d'observations.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

#### Sélection du site d'observations

La zone ci-dessous permet de sélectionner le site d'observations de la session.

![Sélection du site d'observations](images/Session_Site.png)

Le bouton ![Nouveau du site d'observations](images/Session_NewSite_button.png) permet d'ouvrir la boîte de dialogue de création d'un nouveau site d'observations.

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

#### Sélection du répertoire contenant les images de la session

La zone ci-dessous permet de sélectionner le répertoire contenant les images de la session.

![Sélection du répertoire contenant les images de la session](images/Session_RepertoireImages.png)

Le bouton ![Sélection du répertoire contenant les images de la session](images/NewSession_Edit.png) permet de sélectionner le répertoire contenant les images de la session.

> [!TIP]
> A titre personnel, je stock les images de mes session Astro sur un disque dur externe, dans un répertoire nommé `AstroPhotos`.\
Voici le pattern utilisé pour le stockage de mes images :\
`D:\AstroPhotos\[Nom de l'objet]\[Date de la session]\`

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>

#### Commentaires d'une session

La zone ci-dessous permet de positionner un commentaire pour la session.

![Commentaires d'une session](images/Session_Commentaires.png)

<p align="right"><a href="#sommaire">Retour au sommaire</a></p>
