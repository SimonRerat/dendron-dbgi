---
id: 95xu1y8aejfsw1nnhat2qxd
title: Background
desc: ''
updated: 1749816493144
created: 1744614093716
---
## EMI:

The goal of the Earth Metabolome Initiatve (EMI) is, like the Earth Biogenome Project, quite simple, yet ambitious: Document all of the chemical diversity (chimiodiversity) of all known living organisms, while anthropogenic biodiversity loss is speeding up.
In term, this should benefit  human society as a whole, help better understand the chemical fundations of the biosphere, and provide molecular arguments in favor of the protection of biodiversity.

It strives for the creation of a new web of knowledge, linking metabolomics, biology, chemistry, and other open datasets together.
To reach this goal, the EMI team will have to develop  informatical, organisational, and scientific tools tailor made for their needs.
This is where the Digital Botanical Gardens Initiative (DBGI) comes into place (The EMI Consortium, 2022).


## DBGI:

The Digital Botanical Gardens Initiative (DBGI) is designed as a pilot for the EMI. It has a central role to play in it as it is a pilot project created to design, automate, and optimize the workflow leading to metabolomic analysis, while having acces to a species rich, easily accessible, somewhat controlled environment (i.e. botanical gardens).

Its main goal is the collection, management, and sharing of digital informations acquired in living botanical collections. To do so, it focuses on large scale characterisation of the chemiodiverstiy of plants through mass spectrometric approaches.
Not to forget the creation of a knowledge graphe by recouping the informations from many databases (such as Botalista, Open tree of life, LOTUS, ...) to organise, structure and connect them all.
This should help visualise and search the functioning of ecosystems, orient research and conservation efforts.
As the methods of the DBGI while be applied to the EMI, its methods and workflow need to be scalable to match the scale of such an ambitious project. And ultimately, be applicable in wild, hard to access ecosystems.

As of now, only the Jardin Botanique de l'Université de Fribourg (JBUF) and the Jardin Botanique de Neuchâtel (JBN) are part of the initiative. The causes being practical reasons, founding teams have their offices located in Fribourg and Neuchâtel respectively, and ther unique characteristics, the JBUF arranged the System according to the according to the APG IV (UNIFR about JBUF), and the JBN has a plants collection of ethnomedicinal value (The DBGI Consortium, 2022).

## Definition of tree

Defining what a tree is might seem childish at first glance. However, this simple question is all the more relevant as many definitions exist (Lund, 2015), but none seem to be universally agreed upon in botany (Hallé, 2008).

Phylogeny leaves us somewhat clueless to what a tree is, as tree-like growth forms appeared indepentently many time through Life's long history. Indeed, lycopods, ferns, sphenopsids, gymnosperms and many time in angiosperms (palms, dragon tree, "normal trees", ....) (John, Peter, 2007) all came up with their own idea of what we would today call a tree. The first modern tree, _Archaeopteris_ (how do i write in cursive ?) appears during the Devonian period forming large forests. During the Carboniferous, it formed massiv forests along Equisetaceae of the family _Lepidondendron_ (Fairon-Demaret, 1986). Still observable to this day, the tree ferns are also a good exemple of non-spermatophytes arborescent growth forms. (CURSIVE !!)

The JBUF has been using sigils provided in the "Zander. Handwörterbuch der Pflanzennamen", a horticultural dictionnary, as a taxonomic basis. In horticulture, a tree is often described as a plant producing a lignified trunk and reaching a minimum of 4 meters in height in its adult stage. 

A more botanical-scientific way of describing what a tree is would be to use the 8 basic families of the Raunkier system in order to separate the different forms of plants. (insert image of the raunkier system). In our case, all the trees would fall into the category of the phanerophytes. However, this category doesn't allow to differentiate between bush, shrubs, and trees. This, in itself is a big enough problem. The Raunkier system is based on the location of the plant's growth-point during seasons providing adverse conditions, such as cold, and dry seasons. Thus excluding plants living in environment presenting only good seasons, i.e. tropical plants.
As the EMI is a project of international scope, the Raunkier system doesn't seem to provide a relevant definition.
Furthermore, it defines the lignification of the trunk as a necessary criteria for being a tree and the presence of a single trunk. This doesn't include arborescent growth forms people would consider trees such as the banana tree, or the papaya tree.


In this regard, the definition of Francis Hallé seems more suited to the international ideal of the EMI as it doesn't go against the intuition that each person has of what a tree is, independently of time and space.
It reads as follow: 
«Un arbre est une plante habituellement pérenne possédant un ou plusieurs tronc à croissance verticale. Son anatomie rend le tronc autoportant et lui permet d'élever au-dessus des plantes voisines, concurrentes pour la lumière, une cime, ou couronne qui selon les espèces peut avoir trois constitutions différentes: 
    De grandes feuilles si l'arbre n'a pas de branches;
    Des branches qui assurent la photosynthèse si les feuilles sont trop petite pour assurer cette fonction ou absentes;
    Des branches feuillées dans le cas général.
Enfin, l’arbre est un «grand» végétal. Sa hauteur, le diamètre de son tronc, sa longévité sont évalués au regard des dimensions et de la durée de vie de l’être humain.» (Hallé, 2008)

Which could be roughly translated as :
«A tree is a generally perennial plant possessing one or more trunk growing vertically. Its anatomy makes the trunk self-supporting, allowing to rise above its neighbours, competitors for light,a summit, or crown, which, can have tree different constitutions depending on the species:
        Large leaves if the tree deosn't have any branch;
        Branches ensuring photosynthesis if the leaves ar to small to ensure this function, or absent;
        Leafed branches in most cases.
Finally, a tree is a «large» plant. Its height, the diameter of its trunk, its lifespan are evaluated taking human beings as a reference.» 

In short, a tree is a rather large plant, when compared to human standards, which  grows a self-supporting trunk.

## Sample Tracking & UUID
One of the key aspect of this DBGI is establishing and preserving linkage between the field and the database. Therefore, a reliable sample tracking is necessary to keep track of the numerous samples through the entirety of their processing. As soon as a sample has been collected, a unique code is assigned to it. It will follow the it through each stage of preparation, from extraction to storage by being reported on all containers the sample will go through. This allows to efficiently link the data, and the metadat of the sample into the database.

To go further in the labelling process, this Bachelor's project focuses on the introduction of Universally Unique IDentifiers (UUIDs), also known as Globally Unique Identifier (GUIDs) in the established workflow. UUIDs are 128-bit labels used to uniquely identify objects in computer systems. They are excellent for the purpose of the EMI, as they don't need central authority, and can be generated in the field, even in the absence of internet connection.
This will allow the DBGI to be more precise in its metadata assignation as the UUIDs are attributed to sampled individuals. It adds an extra layer of information by giving its own individuality to sampled individuals. This is interesting as each individual differs in state and as such, differs in metabolomic contents.

One important point to keep in mind is that other alternatives to UUIDs such as LSID, URN, HTTP URI, DOI, IGSN, ... exist and are used in different biocollections. The biodiversity community hasn't decided on a single method to use as of yet. No specific method prevails on the others (Guralnik et al. 2015), and the method used by the DBGI might change as time goes on.

