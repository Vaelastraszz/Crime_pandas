# Enquête Criminelle : Résoudre le Meurtre du 22 Juin 2024

## Aperçu du Projet

Le 22 juin 2024, dans la soirée, un meurtre a été commis. L’objectif de ce projet est d’analyser plusieurs jeux de données pour découvrir les détails clés de ce crime, notamment :

- **L'identité du meurtrier**
- **L'arme du crime**
- **La cause du décès**
- **Le lieu du meurtre**

Pour résoudre cette enquête, nous disposons de 8 fichiers CSV qui contiennent des informations importantes. Chaque fichier représente une dimension clé de l'enquête.

<img width="1168" alt="Screenshot 2024-09-12 at 16 13 24" src="https://github.com/user-attachments/assets/842af8e6-4064-4740-82ed-ed681a19cd0d">


## Description des Fichiers CSV

1. **armes.csv**  
   Ce fichier contient des informations sur les armes potentielles utilisées dans le crime.  
   - **Colonnes** :  
     - `arme_id` : Identifiant unique de l'arme  
     - `nom_arme` : Nom de l'arme

2. **autopsie.csv**  
   Ce fichier décrit les résultats de l'autopsie de la victime.  
   - **Colonnes** :  
     - `id_autopsie` : Identifiant unique de l'autopsie  
     - `id_victime` : Identifiant de la victime  
     - `description` : Résultats de l'autopsie (cause de la mort, blessures, etc.)  
     - `date_autopsie` : Date à laquelle l'autopsie a été effectuée

3. **crimes.csv**  
   Ce fichier enregistre les détails du crime commis.  
   - **Colonnes** :  
     - `id_piece` : Identifiant de la pièce où le crime a eu lieu  
     - `date` : Date du crime  
     - `victime_id` : Identifiant de la victime  
     - `id_crime` : Identifiant du type de crime

4. **personnes.csv**  
   Ce fichier contient des informations sur les personnes impliquées dans l'enquête.  
   - **Colonnes** :  
     - `id` : Identifiant unique de la personne  
     - `nom` : Nom de la personne  
     - `age` : Âge de la personne  
     - `metier` : Métier de la personne

5. **pieces.csv**  
   Ce fichier décrit les différentes pièces où les crimes ont pu se produire.  
   - **Colonnes** :  
     - `id` : Identifiant unique de la pièce  
     - `piece_name` : Nom de la pièce

6. **relations.csv**  
   Ce fichier enregistre les relations entre les personnes impliquées.  
   - **Colonnes** :  
     - `id_pers1` : Identifiant de la première personne  
     - `id_pers2` : Identifiant de la seconde personne  
     - `nature_relation` : Nature de la relation (ami, collègue, etc.)

7. **temoignages.csv**  
   Ce fichier contient les témoignages recueillis lors de l'enquête.  
   - **Colonnes** :  
     - `temoignage_id` : Identifiant unique du témoignage  
     - `temoin_id` : Identifiant du témoin  
     - `contenu_temoignage` : Contenu du témoignage  
     - `date_temoignage` : Date à laquelle le témoignage a été recueilli

8. **types_crimes.csv**  
   Ce fichier répertorie les différents types de crimes.  
   - **Colonnes** :  
     - `id` : Identifiant unique du type de crime  
     - `type` : Description du type de crime
