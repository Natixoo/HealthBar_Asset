# HealthBar_Asset

HealthBar_Asset est comme son nom l'indique une asset uniquement pour UNITY et qui sert à créer facilement des barres de vie, de nourritures etc...

Comment l'utiliser ?

Ouvrez Unity et faites un clique droit dans la fenêtre "Project", puis cliquez sur "Import Package" puis sur "Custom Package". Choisissez ensuite le package que vous avez téléchargez et cliquez sur "Import".

<img width="483" alt="Capture d’écran 2021-02-02 à 19 07 44" src="https://user-images.githubusercontent.com/77244944/106644348-49537d80-658b-11eb-867c-1808346f4705.png">

Une fois le package importé, faîtes un clic droit dans la hiérarchie de votre projet et cliquez sur "UI" puis sur "Image". Ouvrez ensuite le dossier HealthBar_Asset et glissez l'élément "BackgroundBar" dans le "Source Image" du component image de l'image que vous venez de créer. Choisissez la couleur de votre HealthBar pour moi ce sera du rouge. Passez ensuite le "Image Type" en "Filled". Vous pouvez si vous le souhaitez jouer avec les paramètres "Fill Method", "Fill Origin" et "Fill Amount" 

![Capture d’écran 2021-02-02 à 18 48 58](https://user-images.githubusercontent.com/77244944/106645263-66d51700-658c-11eb-824c-2cfac0015ae9.png)

Cliquez sur "Add Compenent" et ajoutez le script "HealthBar".

<img width="354" alt="Capture d’écran 2021-02-03 à 16 54 24" src="https://user-images.githubusercontent.com/77244944/106773003-e02e4180-6640-11eb-8092-bed7a8af127c.png">

Pour finir ajoutez de la même façon le script "SetHealth" sur un autre élément de votre scène (comme sur la main camera qui est toujours présente quand vous créez un nouveau projet Unity).

Ouvrez le script "SetHealth" et lisez les commentaires (les lignes en vertes) pour comprendre comment fonctionne cette asset.

Et voilà vous avez maintenant un barre de vie fonctionnelle pour votre jeu !
