# Visual Studio Community vs Entreprise

Cette veille technologique traite des différentes versions de l'IDE de microsoft : Visual Studio 2019.
Je vais donc vous éclairer sur les différents choix à effectuer selon les besoins, les attentes (objectifs)
et les effectifs.  

## Pour commencer

![Visual Studio 2019](https://raw.githubusercontent.com/BidaultMathis/Visual-Studio/master/Veille%20Juridique/Images/vs2019.jpg)

L'IDE Visual Studio est une plateforme de lancement créative avec laquelle vous pouvez modifier, déboguer et générer du code, puis publier une application. Un environnement de développement intégré (IDE) est un programme riche en fonctionnalités qui peut être utilisé pour de nombreux aspects du développement de logiciels. Au-delà de l’éditeur et du débogueur standard fournis par la plupart des IDE, Visual Studio inclut des compilateurs, des outils de complétion de code, des concepteurs graphiques et de nombreuses autres fonctionnalités afin de faciliter le processus de développement logiciel.


## Prérequis

Visual Studio nécessite quelques prérequis système afin de pouvoir travailler convenablement : 

| Systèmes d'exploitation pris en charge|Matériel|Autres composants requis|
|----------|:-------------:|------:|
| Windows 10 version 1703 ou ultérieure : Famille, Professionnel, Éducation et Entreprise|  Processeur 1,8 GHz minimum. Processeur quadruple cœur ou supérieur recommandé, 2 Go de RAM ; 8 Go de RAM recommandé, Espace disque dur : Entre 800 Mo et 210 Go d’espace disponible, Un disque SSD recommandé |  Des droits d’administrateur sont nécessaires pour installer Visual Studio. NET Framework 4.5 est nécessaire pour installer Visual Studio. Visual Studio nécessite .NET Framework 4.7.2, qui est installé pendant l’installation... |

# Versions

Dans quelques instants, nous allons nous intéresser aux différentes fonctionalités que 
proposent ces deux versions de Visual Studio.

 Nous avons d'un coté la version :


```
Community (gratuite)
```

Et de l'autre, la version : 

```
Entreprise (payante)
```

Ces deux version, bien que l'une présente les mêmes fonctionnaltiés que l'autre sont en réalité destinées à différents scénarios d'utilisation.

# Pour qui ?

* Si vous êtes un développeur individuel et si vous ne faites pas de sous-traitance, alors vous pouvez utiliser n'importe quelle version.
* Vous pouvez utiliser l'édition community librement pour des projets OpenSource.
* Si vous êtes un établissement d'enseignement, vous pouvez utiliser CommunityEdition librement (pour un usage éducatif ou en classe)
* Si vous êtes une entreprise avec 250 ordinateurs ou utilisateurs ou plus d'un million de dollars de chiffre d'affaires (filiales comprises), vous n'êtes PAS AUTORISÉ à utiliser l'édition community.
* Si vous n'êtes pas une entreprise telle que définie ci-dessus et que vous ne faites pas d'OSI ou d'éducation, mais que vous êtes une "entreprise" / organisation, avec 5 développeurs simultanés (VS) ou moins, vous pouvez utiliser VS Community librement (mais uniquement si vous êtes le propriétaire du logiciel et le vendez, pas si vous êtes un sous-traitant créant un logiciel pour une entreprise plus grande, un logiciel qui appartiendra à l'entreprise), sinon vous aurez besoin d'une édition payante.

# Les fonctionnalités

Il est l'heure de nous intéresser aux différentes fonctionalités que proposent ces deux versions de Visual Studio. En premier lieu, je vais soumettre les fonctionnalités principales présentes dans les deux versions. Enfin, vous l'aurez deviné, nous allons décrouvrir les fonctionnalités de la version Entreprise que la version Community ne possède pas.

## Lorsque Community et Entreprise ne font qu'un...

### Environnement de développement intégré

![Environnement Dev](https://visualstudio.microsoft.com/wp-content/uploads/2019/03/lightbulb-dark-1200.gif)

* **CodeLens**

```
CodeLens vous permet de rester concentré sur votre travail pendant que vous cherchez ce qui s’est produit dans votre code, sans quitter l’éditeur. Vous pouvez trouver les références à un morceau de code, les changements dans votre code, les bogues liés, les éléments de travail, les revues du code et les tests unitaires.
```

* **Aperçu de définition**

* **Refactorisation**

```
La refactorisation consiste à améliorer votre code après que qu’il a été écrit par la modification de la structure interne du code sans modifier le comportement du code externe.
```

* **Déploiement web en un clic (ASP.NET)**

* **Visionneuse de ressources de modèle**

* **Visualisez les solutions des graphiques de dépendance et Code Maps**

```
Permet d’ouvrir des diagrammes générés dans d’autres versions de Visual Studio en mode lecture seule pour la version community.
```

* **Multi-ciblage**

### Débogage et diagnostics avancés

![Debugs](https://visualstudio.microsoft.com/wp-content/uploads/2019/03/Debugging-1200.gif)

* **Métrique du code**

```
Mesurer la facilité de maintenance du code avec des métriques de code.
```

* **Débogage graphique**

* **Analyse statique du code**

```
La notion d’analyse statique de programmes couvre une variété de méthodes utilisées pour obtenir des informations sur le comportement d'un programme lors de son exécution sans réellement l'exécuter.
```

* **Hub Performances et diagnostics**

### Outil de tests

![Tests](https://visualstudio.microsoft.com/wp-content/uploads/2019/03/test-dark-1200.gif)

* **Test unitaire**

```
Procédure permettant de vérifier le bon fonctionnement d'une partie précise du logiciel ou d'une portion du programme
```

### Développement entre plateformes

* **Remoted iOS Simulator pour Windows**

* **Partager du code entre Android et iOS avec Xamarin**

* **Concepteurs d’interfaces utilisateur iOS et Android natives**

* **Xamarin.Forms**

### Outils et fonctionnalités de collaboration

![Collab](https://visualstudio.microsoft.com/wp-content/uploads/2019/03/liveshare-dark-1200.gif)

* **Création de plans conceptuels PowerPoint**

* **Révision de code**

* **Interruption/reprise des tâches**

* **Team Explorer (prise en charge des outils de développement tiers)**

```
Utilisez la fenêtre d’outil Team Explorer pour coordonner vos efforts de codage avec d’autres membres d’équipe afin de développer un projet, et pour gérer le travail assigné à vous-même, à votre équipe ou à vos projets. Team Explorer connecte Visual Studio aux dépôts Git et GitHub.
```

* **Visual Studio Live Share**

```
Live Share vous permet de partager instantanément votre projet avec un coéquipier. Modifiez et déboguez en temps réel avec vos coéquipiers, sans que ceux-ci aient besoin de cloner un référentiel ou de configurer leur environnement.
```

## Concernant Visual Studio Entreprise...

### Environnement de développement intégré

* **Validation de dépendances dynamique**

* **Diagrammes de couches architecturales**

* **Validation de l’architecture**

* **Clone de code**

### Débogage et diagnostics avancés

* **IntelliTrace**

```
Enregistrer des événements spécifiques

Examiner le code connexe, les données affichées dans la fenêtre Variables locales pendant les événements de débogueur et les informations sur les appels de fonction

Déboguer les erreurs qu'il est difficile de reproduire ou qui interviennent lors du déploiement.
```

* **Intégration du débogueur de la carte du code**

* **Analyse du vidage mémoire .NET**

```
Vous pouvez analyser un instantané pour comprendre l’impact relatif des types d’objets 
sur l’utilisation de la mémoire et pour rechercher 
le code dans votre application qui utilise la mémoire de manière 
inefficace (Possibilité de comparer deux instantanés).
```

* **Débogueur de capture instantanée**

* **Débogage Time Travel (préversion)**

```
Avec TTD, Microsoft donne aux développeurs la possibilité d’enregistrer le code exécuté en production et de rejouer le chemin d’exécution dans Visual Studio. 
TTD vous donne également la possibilité d'avancer et de reculer dans le temps, comme si vous effectuiez un débogage «de boucle interne» localement.
Vous avez également accès à d'importantes fonctionnalités de débogage telles que les sections locales et la pile d'appels.
```
### Outils de test

* **Live Unit Testing**

```
Live Unit Testing exécute automatiquement en arrière-plan tous les tests unitaires affectés, et présente en temps réel
les résultats et la couverture du code dans l’IDE Visual Studio. 
Lorsque vous modifiez votre code, Live Unit Testing fournit des commentaires sur l’impact de vos modifications sur les tests existants et vous indique si le code que vous avez ajouté est couvert par un ou plusieurs tests existants.
```

* **IntelliTest**

```
IntelliTest explore votre code .NET pour générer des données de test et une suite de tests unitaires. 
Pour chaque instruction dans le code, une entrée de test est générée pour exécuter cette instruction. 
Une analyse de cas est effectuée pour chaque branche conditionnelle dans le code. Par exemple, les instructions if, les assertions et toutes les opérations susceptibles de lever des exceptions sont analysées. 
Cette analyse vous permet de générer des données de test pour établir un test unitaire paramétré pour chacune de vos méthodes et de bénéficier d'une couverture de code élevée.
```

* **Microsoft Fakes (isolement de tests unitaires)**

```
Microsoft Fakes vous permet d’isoler le code que vous testez en remplaçant d’autres parties de l’application par des stubs ou des shims. 
Ce sont de petits segments de code qui sont sous le contrôle de vos tests. En isolant votre code pour les tests, vous savez que si le test échoue, la cause réside dans le code et pas ailleurs. 
Les stubs et les shims vous permettent également de tester votre code même si d'autres parties de votre application ne fonctionnent pas encore.
```

* **Couverture du code**

```
Pour déterminer la proportion de code de votre projet qui sera réellement testée par des tests codés, 
par exemple des tests unitaires, recourez à la fonctionnalité de couverture du code de Visual Studio. 
Pour apporter une protection efficace contre les bogues, les tests doivent s'effectuer ou « couvrir » une proportion importante de votre code.
```

### Développement entre plateformes

* **Assemblys incorporés**

* **Xamarin Inspector**

* **Xamarin Profiler**
