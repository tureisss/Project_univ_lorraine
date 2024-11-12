
## Compilation

1. Ouvrez votre terminal ou votre IDE.
2. Naviguez jusqu'au répertoire de votre projet contenant les fichiers `.java`.
3. Compilez le fichier Java `ResourcePlannerApp` avec la commande suivante :

   ```bash
   javac ResourcePlannerApp.java
   ```
4. Si vous utilisez Visual Studio Code, il suffit de cliquer sur le bouton "Run" pour exécuter `ResourcePlannerApp`.

## Exécution

1. Après la compilation, vous pouvez exécuter l'application avec la commande suivante :

   ```bash
   java ResourcePlannerApp
   ```

## Utilisation

### Démarrer l'application

- Vous êtes face à trois boutons : un bouton "Salle", un bouton pour "Professeur" et un bouton "Groupe".
- Choisissez la modification voulue, une page va s'ouvrir selon votre choix de modification.

###### Choix du bouton "Professeur" ######

- Lorsque vous démarrez l'application, une fenêtre graphique s'ouvre avec un bouton "Menu" et un titre "Modificateur de script pour Jikan".
- Sélectionnez le type de professeur que vous souhaitez modifier ou créer en utilisant le menu déroulant.

### Modifier un professeur

1. Choisissez le type de professeur (Extérieurs, Permanents, Voisins) dans le menu déroulant.
2. Sélectionnez un professeur spécifique dans la liste déroulante qui apparaît.
3. Cliquez sur "Modifier professeur" pour ouvrir une fenêtre de modification où vous pouvez changer les détails comme le prénom, le nom ou la couleur, et les contraintes associées au professeur.
4. Cliquez sur "Sauvegarder" pour enregistrer les modifications.

### Supprimer un professeur

1. Suivez les étapes pour sélectionner un professeur.
2. Cliquez sur "Supprimer professeur" pour supprimer le professeur sélectionné.

### Créer un nouveau professeur

1. Sélectionnez "Création" dans le menu déroulant.
2. Remplissez le formulaire avec le prénom et le nom du professeur.
3. Sélectionnez le type de professeur et choisissez une couleur.
4. Cliquez sur "Créer Professeur" pour ajouter le nouveau professeur.

###### Choix du bouton "Groupe Etudiants" ######

- Lorsque vous démarrez l'application, une fenêtre graphique s'ouvre avec un bouton "Menu" et un titre "Modificateur de script pour Jikan".
Vous avez également un menu déroulant (Combobox) contenant les 3 promotions de l'année 2023-2024, ainsi qu'un fichier "TEST" et un fichier "aCharger" qui contient les noms des autres fichiers cités auparavant.
- Vous avez ainsi le choix de Modifier un de ces fichiers (Boutton Modifier), en ajouter 1 (Boutton Ajouter), ou en supprimer un (Boutton Supprimer).

### Ajouter une Promotion

1. Cliquez sur le Boutton vert "Ajouter".
2. Une interface de dialogue s'ouvre, Ecrivez le nom que vous voulez donner à votre nouveau fichier pui appuyez sur "OK".
3. Une seconde interface va s'ouvrir, avec un espace à droite afin d'insérer le contenu de votre fichier, puis la partie à gauche contenant les instructions pour chaque ligne (afin de convenir au format de jikan). 

Note: Si vous avez besoin des codes couleurs RVB, il vous suffit de cliquer sur le boutton portant ce nom. 
Note: Un mauvais format lorsque vous insérez le contenu du fichier, donc le non-respect des consignes à gauche de l'écran ne va pas permettre d'ajouter le fichier au jikan, voir, bloquer la compilation.

4. Validez l'ajout du Boutton en appuyant sur "Confirmer" en vert.  (une note va apparaître à l'écran pour valider l'opération).

### Modifier une Promotion

1. Cliquez sur le Boutton "Modifier".
2. Une interface s'ouvre, contenant un menu déroulant. Lorsque vous choisissez un fichier, son contenu s'ouvre juste en-dessous.
3. Libre à vous de modifier le fichier directement là ou son contenu est affiché, dans la zone de texte.
4. N'oubliez pas de cliquer sur le Boutton "Enregistrer".

### Supprimer une Promotion

1. Cliquez sur le Boutton "Supprimer".
2. Choisissez dans le menu déroulant quel fichier vous souhaitez supprimer et sélectionnez-le.
3. Cliquez sur "Supprimer" en rouge.

###### Choix du bouton "Salle" ######

- Lorsque vous démarrez l'application, une fenêtre graphique s'ouvre avec un bouton "Menu" et un titre "Modificateur de script pour Jikan".
- Sélectionnez le type de professeur que vous souhaitez modifier ou créer en utilisant le menu déroulant.

### Ajouter une Salle

1. Cliquer sur Nouveau en bas de page.
2. Sélectionnez la catégorie de cours dans le premier menu déroulant.
3. Entrez le nom abrégé de la nouvelle salle dans le champ prévu à cet effet.
4. Cliquez sur le bouton "Choisir Couleur" pour sélectionner la couleur de la salle.
5. Cliquez sur "OK" pour ajouter la nouvelle salle.
6. Un message apparaîtra pour confirmer si la salle a été ajoutée avec succès.

### Modifier une Salle

1. Sélectionnez la catégorie de cours dans le premier menu déroulant.
2. Choisissez une salle dans la liste déroulante.
3. Cliquez sur "OK" en bas de page afin de valider la sélection.
4. Modifiez les détails selon vos besoins.
5. Cliquez sur "OK" pour enregistrer les modifications.
6. Un message de confirmation apparaîtra si les modifications sont enregistrées avec succès.

### Supprimer une Salle

1. Sélectionnez la catégorie de cours dans le premier menu déroulant.
2. Choisissez une salle dans la liste déroulante.
3. Cliquez sur le bouton "OK" dans le but de valider la sélection.
4. Cliquez sur le bouton "Supprimer".
5. Un message apparaîtra pour confirmer si la salle a été supprimée avec succès.