# Expo
Expo est une application qui va nous permettre de développer une app avec React-Native et de se passer de XCode ou d’Android Studio. Expo propose une CLI et un espace de développement avec une interface graphique. Il suffit de cliquer sur `New Project > blank > Create` et ensuite laisser Expo créer le projet de votre application.

## Structure du projet
La structure du projet est un peu différente de celle créé par la CLI de ReactNative. Vous ne disposez plus que d'un seul fichier `.js` qui vous servira d'index pour la réalisation de votre application. Il est possible de modifier le nom du fichier principal utilisé par l'application dans le fichier `package.json`

## API (+ et -)
Il n'est pas possible d'installer de composants externes dans Expo. Vous disposez uniquement des composants disponible (ici)[https://docs.expo.io/versions/latest/sdk/map-view.html]. Tout ce qui requiert un `react-native link` ne fonctionnera pas sur Expo.

## Ejecting
Éjecter votre application revient à créer une version native pour chaque plateforme. Cette commande n'est pas réversible. Pour éjecter, il est souhaitable d'utiliser ExpoKit afin de rentre les composants Expo disponible comme une librairie. Il est donc important de bien réfléchir aux fonctionnalités de votre application avant de choisir l'une ou l'autre option.
