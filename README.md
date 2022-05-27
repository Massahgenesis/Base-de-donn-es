# Database
Requête pour ajouter un film: INSERT INTO'LocationDeFilm'.ListedesFilms'('codeliste', 'titre de sortie','durée','réalisateur')VALUE(",",",");
Requête pour modifier un film: UPDATE 'ListesDesFilms' SET 'code' = '' WHERE 'Code' = '' ;
Pour supprimer un film: DElETE FROM 'Listesdesfilms' WHERE code= '' ;
requête pour ajouter un client:INSERT INTO 'ListesdesClients' ('Nom','Prenom','mail') VALUE (",",");
requête pour modifier un client:UPDATE ListeDesClients SET Nom = '' WHERE Nom = '';
requête pour supprimer un client:DELETE FROM ListesDesClients WHERE code = '' ;
requête pour ajouter les trois dernires fils ajoutés:SELECT * FROM ListesDesFilms WHERE Films = '3' order by desc;
