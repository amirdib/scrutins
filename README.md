# L'objectif

L'objectif est d'établir une cartographie politique par analyse écologique.
Le premier objectif est de générer de compiler les données +suivante+s :
 * présidentielles 2007
 * présidentielles 2012
 * législatives 2012
 * européennes également

En exploitant les données par bureau de vote et en calculant les transferts.
 
L'objectif est aussi de répérer les régions avec un fort vote NON "de gauche" au référendum de 2005.


# Comment ?

Les cartes sont générées à partir d'un fichier SVG et de feuilles de style XSLT.

```
sudo apt-get install libsaxonb-java basex inkscape
```

```
make maps
```

```make clean``` supprime les fichiers temporaires.
