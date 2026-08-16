# Application Tourisme Chaumeré

Cette application est une WebView pointant sur le site https://clarteweb35.github.io/autour-de-rennes/agenda/.

## Instructions de compilation :

1. Assurez-vous d'avoir [Node.js](https://nodejs.org/) installé.
2. Installez Capacitor CLI : `npm install -g @capacitor/cli`
3. Installez les dépendances : `npm install`
4. Ajoutez la plateforme Android : `npx cap add android`
5. Ouvrez Android Studio : `npx cap open android`
6. Dans Android Studio :
   - Configurez votre `signingConfig` dans le fichier `build.gradle` (module app).
   - Allez dans **Build > Build Bundle(s) / APK(s) > Build Bundle(s)** pour générer le .aab.
