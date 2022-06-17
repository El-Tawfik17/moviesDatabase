Voici les differentes requêtes
<!-- Requête pour ajouter un film -->
INSERT  INTO moviesdb.films(title,duration, out_date,realisator) values('nom_du_film','durée_du_film','date_de_sortie',nom_du_realisateur)

<!-- Requête de Modification d'un films -->
UPDATE moviesdb.films SET=nom_de_la_column_concerne='valeur_de_modification' WHERE id=id_de_la column_concerne


<!-- Requête de suppression d'un films -->

delete from moviesdb.films where title='le_nom_du_film'

<!-- Requête d' ajoute d'un client  -->
INSERT INTO moviesdb.customers(first_name,last_name,email) values('prenom_du_client','nom_de_famille_client','email_client')

<!-- Requête pour modifier un client -->
UPDATE moviesdb.customers SET=nom_de_la_column_concerne='valeur_de_modification' WHERE id=id_de_la_column_concerne

<!-- Requête pour supprimer un client -->
delete from moviesdb.customers where first_name= 'prenom_client' and last_name='nom_client'

<!-- Requête pour afficher les 3 derniers films ajoutés -->

SELECT*FROM moviesdb.films ORDER BY id DESC LIMIT 3