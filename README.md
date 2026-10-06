<img width="1915" height="1078" alt="Screenshot 2026-10-06 175505" src="https://github.com/user-attachments/assets/638c92ed-36f2-45fa-bcf2-7b2013436ede" />
<img width="1892" height="977" alt="Screenshot 2026-10-06 175524" src="https://github.com/user-attachments/assets/e3416796-b049-469e-86bd-946abf5f00ac" />


Ce projet est une application Java qui utilise JPA avec Hibernate pour gérer des produits dans une base de données H2 en mémoire. Le projet est construit avec Maven et fonctionne avec Java 21.

L'entité Produit possède trois attributs : un identifiant généré automatiquement (id), un nom (nom) et un prix (prix). Au lancement, Hibernate lit la configuration du fichier persistence.xml et crée automatiquement la table PRODUIT.

Le programme principal (App.java) effectue les opérations suivantes :

Insertion de trois produits dans la base.
Affichage de la liste de tous les produits.
Recherche d'un produit par son identifiant (ID = 2).

Les requêtes SQL générées par Hibernate s'affichent dans la console. La console web H2 (http://localhost:8082) permet aussi de consulter directement le contenu de la table avec SELECT * FROM PRODUIT. Elle confirme que les trois produits sont bien enregistrés.
