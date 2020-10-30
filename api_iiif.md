# API IIIF

Jean-Damien Généro, ingénieur d'études au Centre Maurice-Halbwachs (UMR 8097 CNRS/EHESS/ENS).

## API Internet Archive

* Doc : [IA IIIF FAQs](https://archive.readme.io/docs/ia-iiif-faqs)

* Lien de la visionneuse IIIF : `https://iiif.archivelab.org/iiif/<item id>` ([exemple](https://iiif.archivelab.org/iiif/lesouvriersdesde03sociuoft)).

* Lien vers une seule image (full) : `https://iiif.archivelab.org/iiif/<item id>$<page id>/full/full/0/default.jpg` ([exemple](https://iiif.archivelab.org/iiif/lesouvriersdesde03sociuoft$34/full/full/0/default.jpg)).

* Lien vers une région dans l'image : `https://iiif.archivelab.org/iiif/<item id>$<page id>/<region>/full/<rotation>/default.jpg` où `<region>` est composé de quatre données séparées par une virgule (pixel l'axe horizontal, pixel l'axe vertical, pixels de largeur, pixels de hauteur) et `<rotation>` la valeur de la rotation de l'image, par défaut `0` ([exemple](https://iiif.archivelab.org/iiif/TheGeometry$1/-1602,175,793,396/full/0/default.jpg)).

* Lien vers le cropper tool : `https://iiif.archivelab.org/iiif/<item id>$<page id>` ([exemple](https://iiif.archivelab.org/iiif/lesouvriersdesde03sociuoft$34)) -> ne fonctionne pas.

## API Gallica

* Doc : [API IIIF de récupération des images de Gallica](http://api.bnf.fr/api-iiif-de-recuperation-des-images-de-gallica)

* Lien vers une seule image (full) : `https://gallica.bnf.fr/iiif/ark:/<ark id>/f<page id>/full/full/0/native<format : .jpg ou .png>` ([exemple](https://gallica.bnf.fr/iiif/ark:/12148/bpt6k633133/f29/full/full/0/native.jpg))

* Lien vers une région dans une image : `https://gallica.bnf.fr/iiif/ark:/<ark id>/f<page id>/<region>/full/<rotation>/native<format : .jpg ou .png>` où `<region>` est composé de quatre données séparées par une virgule (pixel l'axe horizontal, pixel l'axe vertical, pixels de largeur, pixels de hauteur) et `<rotation>` la valeur de la rotation de l'image, par défaut `0` ([exemple](https://gallica.bnf.fr/iiif/ark:/12148/bpt6k633133/f29/780,3520,1848,668/full/0/native.jpg))



