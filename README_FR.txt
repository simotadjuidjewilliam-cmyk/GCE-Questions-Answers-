GCE ANSWERS — PROJET ANDROID (DEMO)
Powered by Tadjuidje Labs

CE QUE CE PROJET EST
- Une enveloppe Android native utilisant WebView.
- L'interface HTML de démonstration est embarquée dans app/src/main/assets/index.html.
- Les données de démonstration sont conservées localement dans le navigateur WebView.
- Le sélecteur de fichiers Android est activé pour choisir une photo depuis la galerie.
- Les liens externes (dont WhatsApp) s'ouvrent dans les applications correspondantes.

CE QUE CE PROJET N'EST PAS
Ce n'est pas encore une application prête pour la commercialisation. Le compte candidat, l'activation Premium, les contenus et le panneau admin de la démo restent locaux à l'appareil et ne sont pas sécurisés pour gérer de vrais abonnés. Neuro AI ne répond pas réellement sans backend et clé API conservée côté serveur. Aucun paiement n'est traité dans l'app.

COMMENT GENERER UN APK
1. Installer Android Studio (version récente) sur un ordinateur.
2. Installer Android SDK Platform 35 et un JDK compatible (Android Studio fournit généralement son JBR).
3. Ouvrir le dossier GCE_Answers_Android_Project dans Android Studio.
4. Laisser Gradle synchroniser le projet.
5. Menu Build > Build Bundle(s) / APK(s) > Build APK(s).
6. Android Studio produira l'APK de debug dans app/build/outputs/apk/debug/.

IDENTIFIANT ANDROID
com.tadjuidjelabs.gceanswers

AVANT UNE PUBLICATION
Il faudra remplacer les fonctions locales par un backend sécurisé, mettre en place l'authentification, une base de données partagée, l'administration protégée, la vérification réelle des abonnements, l'API IA côté serveur, les archives GCE authentifiées, les sauvegardes, la politique de confidentialité et les tests de sécurité.
