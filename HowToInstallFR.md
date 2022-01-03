# Comment installer ACT FFXIV Mini Parse

## 1 - Installer Advanced Combat Tracker (ACT) et le plugin FFXIV

Rendez-vous sur cette page : https://advancedcombattracker.com/download.php et télécharger la dernière version de ACT et du plugin FFXIV.

![Display](https://raw.githubusercontent.com/Jericho1060/ffxiv-miniparse/main/resources/doc_download.png)

Une fois les deux fichiers téléchargés, lancer l'installation d'ACT en éxécutant `ACTv3-Setup.exe` et validant chaque étapes.

Vous pouvez extraire l'archive `FFXIV_ACT_Plugin_2.6.3.3.zip` (clic droit => extraire tout => Extraire).

Copiez le dossier extrait dans un répertoire sûr que vous ne supprimerais pas par accident ou, dans le dossier par défaut des plugins
ACT : `C:\Users\%username%\AppData\Roaming\Advanced Combat Tracker\Plugins`

## 2 - Télécharger le OverlayPlugin

Rendez-vous sur cette page : https://github.com/RainbowMage/OverlayPlugin/releases et télécharger la version correspondant a vôtre système d'exploitation :

- x86 pour un système 32 bits
- x64 pour un système 64 bits

![Display](https://raw.githubusercontent.com/Jericho1060/ffxiv-miniparse/main/resources/doc_download_overlay.png)

Vous pouvez extraire l'archive et la copier au même endroit que le plugin FFXIV.

## 3 - Télécharger le MiniParse

Rendez-vous sur cette page : https://github.com/Jericho1060/ffxiv-miniparse/releases et téléchargez l'archive de la dernière version.

![Display](https://raw.githubusercontent.com/Jericho1060/ffxiv-miniparse/main/resources/doc_download_miniparse.png)

Comme pour les deux archivez précédentes, extrayez le contenu et copiez le dans le même dossier.

## 4 - Activer les plugins dans ACT

Lancez ACT et rendez-vous dans l'onglet `Plugins` puis dans l'onglet `Plugin Listing`.

![Display](https://raw.githubusercontent.com/Jericho1060/ffxiv-miniparse/main/resources/install_act_plugins.png)

Puis cliquez sur le bouton `Browse` et allez dans le dossiez où vous avez copié tous les dossiers.

![Display](https://raw.githubusercontent.com/Jericho1060/ffxiv-miniparse/main/resources/install_act_browse_dirs.png)

Ouvrez le dossier `FFXIV_ACT_Plugin_x.x.x.x` (les x désignent ici la version du plugin, les nombres peuvent changer en fonction de la version actuelle au moment où vous installer
le plugin), sélection le fichier `FFXIV_ACT_Plugin.dll` et validez en cliquant sur le bouton `Ouvrir`.

De retour sur ACT, cliquez sur le bouton `Add/Enable Plugin`.

Renouvelez l'opération avec le dossier `OverlayPlugin-0.3.3.9-x64-full` (le nom peut aussi changer en fonction de la version) et sélectionnez le fichier `OverlayPlugin.dll`,
attention, il y a plusieurs fichiers DLL dans ce dossier, sélectionnez bien le bon. cliquez a nouveau sur `Add/Enable Plugin` pour l'activer.

Vous devriez voir maintenant les deux plugins dans la liste en dessous avec la case `Enabled` sélectionnée.

![Display](https://raw.githubusercontent.com/Jericho1060/ffxiv-miniparse/main/resources/install_act_plugins_enabled.png)

## Réglages du plugin FFXIV

Cliquez sur l'onglet `FFXIV ACT Plugin` puis sélectionnez la langue dans laquelle votre jeu est configuré.

Vous pouvez aussi changer la valeur de la liste `Parse Filter` en `Party` pour n'afficher que la liste des membres de votre groupe. Afficher tout le monde, dans un raid à 2 joueurs
n'est pas toujours facile à lire.

Vous pouvez aussi cocher la case `Disable Combine Pets with Owner` pour afficher les informations des familiers (comme les invocations) séparément de ceux ou celles à qui elles
sont liées.

![Display](https://raw.githubusercontent.com/Jericho1060/ffxiv-miniparse/main/resources/install_act_plugins_ffxiv_settings.png)

## Réglages de l'overlayPlugin et activation du skin miniparse

Cliquez maintenant sur l'ongler `OverlayPlugin.dll` puis sur le sous onglet `Mini Parse`.

Vérifiez que la case `Show Overlay` est bien cochée (vous pouvez aussi activer l'option `Enable clickthru` pour que le mini parse ne soit pas clickable, vos clics passeront au
travers dans ce cas et l'overlay ne gènera pas avec votre jeu).

Cliquez ensuite sur le bouton `...` en bout de ligne en face de l'option `URL` et ouvrez à nouveau le dossier où vous avez tout copié, rendez vous dans le dossier `ffxiv-miniparse`
et sélectionnez le fichier `Torgan.MiniParse.html` puis validez en cliquant sur le bouton `Ouvrir`.

![Display](https://raw.githubusercontent.com/Jericho1060/ffxiv-miniparse/main/resources/install_act_plugins_overlay_settings.png)
