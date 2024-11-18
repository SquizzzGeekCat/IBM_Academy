Le resutats des exo uml est stocker ici

enoncer exo 1 :
Exercice : Le cas MonAuto

MonAuto est une entreprise qui fait le commerce,
l'entretien et les réparations de voitures.
MonAuto désire exploiter un logiciel de gestion des
réparations; elle dispose déjà d'un logiciel
comptable. Les factures de réparations seront
imprimées et gérées par le logiciel comptable.
Le logiciel de gestion des réparations devra
communiquer avec le logiciel comptable pour lui
transmettre les réparations à facturer.

Exercice : Le cas MonAuto (suite)

Le logiciel de gestion des réparations est destiné en priorité au chef
d'atelier, il devra lui permettre de saisir les fiches de réparations
et le travail effectué par les divers employés de l'atelier.
Pour effectuer leur travail, les mécaniciens et autres employés
de l'atelier vont chercher des pièces de rechange au magasin.
Lorsque le logiciel sera installé, les magasiniers ne fourniront
des pièces que pour les véhicules pour lesquels une fiche de
réparation est ouverte; ils saisiront directement les pièces
fournies depuis un terminal installé au magasin.
Lorsqu'une réparation est terminée, le chef d'atelier va essayer la
voiture. Si tout est en ordre, il met la voiture sur le parc clientèle
et bouclera la fiche de réparation informatisée. Les fiches de
réparations bouclées par le chef d'atelier devront pouvoir être
importées par le comptable dans le logiciel comptable. 

Exercice : Le cas MonAuto (suite)
• Découvrez les besoins implicites
• Nous n'avons pas explicité la manière dont les
employés et leur qualification sont gérés, tout
comme pour le stock de pièces de rechange, les
clients, les employés, les ventes de voitures...
Nous pouvons imaginer que le logiciel de
gestion des réparations offre les fonctionnalités
implicites de gestion des clients, employés,
ventes de voitures, pièces de rechange...

Exercice 2 : Archéologie

La société royale d’archéologie automobile vous
embauche pour réaliser un système de support aux
archéologues lors des fouilles.
Un archéologue lors d’une fouille réalise le croquis d’une
pièce sur son tablet PC et l’envoie au serveur de
l’association. Pour ce faire il ouvre un nouveau dessin et
commence à dessiner. Il a également la possibilité de
copier des éléments à partir d’un ancien dessin. Après
avoir défini un certain nombre de propriétés pour son
dessin (résolution, nombre de couleurs,…),
l’archéologue envoie son dessin au serveur de bases de
données en indiquant où le fichier doit être stocké et par
qui il peut être vu.

Exercice 2 : Archéologie (suite)

On vous demande d’adapter le système. Les
archéologues de terrain sont de deux types, les
archéologues apprentis et les archéologues
confirmés. Pour assurer la qualité de la base de
données, seuls les confirmés peuvent réaliser et
envoyer des croquis au serveur. Néanmoins, les
archéologues apprentis peuvent envoyer des
notes de type texte (prises sur leur Tablet PC).
Cette faculté est également accessible aux
confirmés. Ces notes seront disponibles pour
tous via le site web de l’association. 