# TOPen25
Recréation du style des cartes "TOP25" de l'IGN, en cartocss

Seul le zoom 15, correspondant à peu près au 1:25000 est supporté.

Même si le gros oeuvre est fait, les finitions vont prendre du temps 
et pour mieux les gérer, j'ai ouvert ce projet github pour le suivi 
des bugs et les demandes d'améliorations :

https://github.com/cquest/topen25/issues

N'hésitez pas à contribuer, si possible en fournissant un lien vers la zone en question sur https://osm.cquest.org/topen25/

L'objectif
 est d'avoir un rendu approchant des cartes au 1:25000, mais il ne 
pourra sûrement par être identique à 100% car une partie semble faite "à
 la main", en particulier sur les surcharges concernant le relief. 
J'envisage aussi de l'étendre à d'autres échelles (ou niveaux de zoom).

Le
 résultat pourra être publié à terme sous forme de fichiers MBtile ou geopackage
 pour être utilisé sans connexion par des applis sur smartphone. Merci 
donc de ne pas "aspirer" les tuiles.

Pour avoir une qualité 
optimale d'affichage sur les écrans hdpi de nos smartphones, il est 
généré en résolution double "retina". Cela prends en 3 à 4 heures de 
calculs sur ma station de travail et pèse au final 41Go pour la France 
entière. Tout cela est auto-hébergé depuis ma baie de serveurs située 
dans ma cave avec une double connexion par fibre.

Ah oui, dernier 
point... les itinéraires de randonnées n'étant pas sous licence libre 
(la FFRP estimant avoir un droit d'auteur sur les GR©/PR©), ils ne 
seront pas ajoutés. D'autres itinéraires sous licence libre pourraient 
par contre être ajoutés... à voir si cela se fait dans une couche 
transparente à part.


## Données utilisées

- BD Topo IGN (dernier millésime, soit celui de décembre 2020 à la date de rédaction de ce README)
- BD Alti 75m (pour l'ombrage et les courbes de niveau)

Ces données sont sous Licence Ouverte 2.0 depuis janvier 2021.
