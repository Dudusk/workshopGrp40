Création application Cordova Commandes : 

Dans le dossier où il y a le site : 

1. 

cordova create CordovaProject io.cordova.hellocordova CordovaApp

•	CordovaProject is the directory name where the app is created.
•	io.cordova.hellocordova is the default reverse domain value. You should use your own domain value if possible.
•	CordovaApp is the title of your app.


2.

a. cordova platform add android

b. <u>Les OS :</u> 
cordova platform add wp8
cordova platform add amazon-fireos
cordova platform add windows
cordova platform add blackberry10
cordova platform add firefoxos

c. IOS : 
cordova platform add IOS

3. 

Remove platforme : cordova platform rm android


4. 
Aller dans le dossier créer "CordovaProject"

Build de l'application : cordova build 
Emulation de l'application : cordova emulate