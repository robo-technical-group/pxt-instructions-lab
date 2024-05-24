# Des conseils pour les tutoriels et les skillmaps

Voice des conseils que j'ai découvertes quand on écrit les tutoriels et les skillmaps.

-   Testez vos tutoriels et skillmaps dans des fenêtres « private » ou « incognito ». Tout problème avec les autorisations devrait apparaître de cette façon.
-   Les serveurs de MakeCode peuvent mettre en cache vos tutoriels et skillmaps. Pour cette raison, vous devrez pousser une nouvelle version chaque fois que vous apporterez un changement. Cela m'amène à mon prochain conseil !
-   Vous avez *vraiment* besoin de faire la gestion des fichiers de code source avec un éditeur MakeCode. Le fichier `pxt.json` est crucial pour le fonctionnement de vos tutoriels et de vos cartes de compétences. S'il est malformé ou s'il manque quelque chose, quelque chose se cassera probablement.
-   Une fois que vous avez créé le projet dans un éditeur MakeCode et que vous l'avez envoyé à GitHub, vous pouvez utiliser n'importe quel outil de votre choix pour modifier des fichiers existants (par exemple, Visual Studio Code).
-   Pour ajouter de nouveaux fichiers Markdown, utilisez l'outil d'exploration de fichiers dans un éditeur MakeCode. Cela permettra de s'assurer que le fichier `pxt.json` est correctement mis à jour.
-   Vous pouvez utiliser un autre outil de gestion Git (par exemple, GitHub CLI, Visual Studio Code) pour envoyer les ressources utilisées dans vos tutoriels et skillmaps (par exemple, des images) vers votre référentiel GitHub.
-   Utilisez un éditeur MakeCode pour pousser les nouvelles versions de votre projet. La création d'une version à l'aide d'outils Git standard ne purgera pas les données mises en cache des serveurs de MakeCode.
-   Si un didacticiel ou une carte de compétences utilise des ressources personnalisées (par exemple, des images d'arrière-plan, des animations de sprites, des mélodies), créez un référentiel distinct qui servira de « pack de ressources / asset pack ».
-   Les skillmaps doivent avoir un modèle de code dans chaque tutoriel afin que les étudiants conservent leur code le long de chaque chemin. Reportez-vous au [message de Richard sur le forum MakeCode](https://forum.makecode.com/t/tutorial-creators/19464/60) pour plus d'informations.
