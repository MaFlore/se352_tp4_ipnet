# se352_tp4_ipnet

TP4 : JPA (EJB SESSION)
Grace à vos connaissances en JPA :

1) Classes : créer les classes Java qui correspondent à la base de données des étudiants d’un département. 
• Etudiant : qui représente un étudiant du département. Les informations de l’étudiant retenues sont données par le nom, 
le prénom, l’email, l’adresse et son numéro de téléphone. 
• Cours : qui représente un cours dispensé aux étudiants. 
Les informations d’un cours sont données par l’intitulé et la date. 
• Département : avec le nom et l’adresse web comme information à retenir. 
• Professeur : avec comme information le nom, le prénom, le grade et l’email.

2) Associations : 
• Un étudiant peut suivre plusieurs cours et plusieurs étudiants peuvent suivre le même cours. 
• Un étudiant appartient ne peut s’inscrire dans un département. • Un enseignant peut dispense plusieurs cours dans différents département. 
• Un département à plusieurs professeurs et un professeur peut appartenir à plusieurs départements. 
• Les associations entre les professeurs et les départements, entre les étudiants et les cours et entre les professeurs et les cours sont bidirectionnelles.

3) Enregistrement dans la base de données 
- Créer une classe de test appelée Principale et qui contient une méthode main. 
- Créer quatre étudiants puis enregistrez les dans la base de données. 
- Créer un département biologie végétale et un département informatique. 
Le premier et le dernier étudiant enregistrés dans la table étudiant sont dans le département informatique. 
Trois professeurs dont un biologiste, un informaticien et un mathématicien sont récemment recrutés par l’université pour dispenser respectivement la biologie moléculaires, 
la programmation orientée objet et l’analyse numérique. Seule la mathématique est dispensée dans les deux départements. 
Exécuter la méthode main et vérifier que la base de données contient les données persistantes

4) JPQL
Requêtes dynamiques : 
- Ecrire une requête qui récupère tous les étudiants de l’université et affiche leurs noms. 
- Ecrire une deuxième requête qui ne récupère pas les étudiants mais seulement leur nom, prénom et numéro de téléphone.
Requêtes nommées : 
- Ecrire une requête qui affiche le nom des professeurs. 
- Ajouter un cours de parasitologies des plantes et parasites et statistique dans le département biologie et attribuer les cours aux professeurs selon leur spécialité. 
- Ajouter trois étudiants de plus dans le département biologie végétale. 
- Afficher le nom, prénom et adresse des étudiants en biologie. 
- Modifier et afficher les adresses des étudiants en biologie.
