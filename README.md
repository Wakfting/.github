# Wakfting

Wakfting est une application mobile conçue pour améliorer votre expérience de jeu sur Wakfu, le célèbre jeu d'Ankama. En intégrant une variété d'outils et de fonctionnalités dans une interface conviviale, Wakfting vise à faciliter la gestion de vos activités dans le jeu.

L'une des principales caractéristiques de Wakfting est le gestionnaire de craft, qui vous permet de suivre et de gérer vos crafts dans le jeu. Que vous fabriquiez des objets pour votre usage personnel ou pour les vendre sur le marché, cette fonctionnalité vous aidera à rester organisé et à maximiser votre efficacité.

De plus, Wakfting comprend un suivi des ressources. Avec cette fonctionnalité, vous pouvez facilement voir combien de chaque ressource vous avez, ce qui vous aide à planifier vos crafts et à savoir quand vous devez rassembler plus de ressources.

Le suivi des kamas est une autre fonctionnalité clé. En gardant une trace de vos kamas, vous pouvez mieux gérer vos finances dans le jeu et vous assurer que vous avez suffisamment de kamas pour toutes vos dépenses.

En outre, Wakfting offrira une map interactive qui vous montre où trouver des ressources spécifiques, ainsi que les routes optimales pour les récolter. Cette fonctionnalité est particulièrement utile pour les artisans qui ont besoin de rassembler régulièrement des ressources spécifiques.

Veuillez noter que toutes ces fonctionnalités ne sont pas encore disponibles, mais qu'elles sont prévues pour les futures mises à jour de l'application.

# Le compte

Lorsque vous lancez l'application Wakfting pour la première fois, la première chose que vous verrez est une page de génération de mnémonique. Pourquoi une mnémonique ? En raison des restrictions d'Ankama concernant le traitement des données personnelles, une mnémonique est utilisée pour générer un identifiant unique pour chaque utilisateur. Cela signifie que votre identité réelle ou votre pseudo ne sont jamais liés à votre compte Wakfting.

L'un des principaux avantages de l'utilisation d'une mnémonique est que vous pouvez restaurer votre compte à tout moment, à condition de ne pas perdre vos mots de mnémonique. C'est une mesure de sécurité essentielle qui garantit que vous n'aurez jamais à vous soucier de perdre l'accès à votre compte. Par ailleurs, cela permet de maintenir un haut niveau d'anonymat, car rien ne peut relier votre compte Wakfting à une identité réelle ou à un pseudo.

C'est une fonctionnalité qui assure à la fois la sécurité de vos informations et le respect de votre vie privée, tout en vous permettant de profiter pleinement de toutes les fonctionnalités que Wakfting a à offrir.

## Liste des items

La première page de l'application est la liste des items. Ici, vous pouvez filtrer et trier les objets en fonction de vos besoins. En cliquant sur un item, vous accédez à la page détaillée de l'item, qui vous fournit des informations supplémentaires sur l'objet, à condition que ces informations soient disponibles dans la base de données. De plus, cette page vous offre deux options : ajouter l'item à vos crafts ou suivre le prix de l'item.

## Mes Crafts

La page "Mes Crafts" vous permet de gérer les items que vous souhaitez fabriquer. Vous pouvez développer chaque item pour voir ses ingrédients et ajouter ou supprimer des items en fonction de ce que vous avez. Vous pouvez également modifier la quantité de l'item que vous voulez fabriquer. Si vous avez ajouté le client de bureau, vos crafts seront automatiquement mis à jour. De plus, lorsque vous êtes prêt à fabriquer un item, une notification apparaîtra pour vous le signaler.

## Suivi des prix

La page "Suivi des prix" vous permet de sélectionner l'item dont vous souhaitez suivre le prix. Vous pouvez ajouter le prix minimum et maximum chaque jour, ce qui génère un graphique quotidien des prix avec la moyenne mobile, le prix minimum et le prix maximum au fil des jours. Cela vous permet de suivre l'évolution des prix et d'identifier les tendances. 

Nous envisageons également de mettre en place un système de partage des prix des ressources. Ce système permettrait de mettre en commun les informations de suivi si vous le souhaitez. De plus, il pourrait vous notifier lorsqu'une ressource est à un prix intéressant pour la vente ou pour l'achat, selon vos préférences. Cette fonctionnalité vise à améliorer encore plus la gestion de vos ressources et à maximiser votre efficacité dans le jeu.

## Paramètres

Enfin, la page "Paramètres" vous permet de personnaliser votre expérience sur l'application. Vous pouvez changer la langue, réinitialiser votre compte ou récupérer votre identifiant. C'est également ici que vous pouvez lier l'application web à votre compte.

## API

L'API de Wakfting, basée sur Express, est connectée à une base de données MongoDB. Elle assure une multitude de fonctions essentielles pour l'efficacité et la fluidité de l'application.

Parmi ces fonctions, l'API permet la récupération des items avec des filtres. Cela signifie qu'elle peut récupérer des données spécifiques depuis la base de données en fonction de critères définis, comme le type d'item ou sa rareté. Ces informations sont ensuite reformatées pour être compatibles avec le front-end de l'application.

De plus, l'API est capable de récupérer des items individuellement. Cela permet à l'utilisateur de visualiser des informations détaillées sur un item spécifique, comme sa description, son prix, ou même ses statistiques.

En outre, l'API facilite l'ajout d'items à l'inventaire. Grâce à elle, les utilisateurs peuvent ajouter de nouveaux items à leur inventaire, soit en les créant eux-mêmes, soit en les achetant sur le marché.

Enfin, l'API gère également les prix des items. Elle permet de mettre à jour les prix des items en temps réel, ce qui garantit que les utilisateurs ont toujours accès aux informations les plus récentes et les plus précises possible. Cette fonctionnalité est particulièrement utile pour les utilisateurs qui cherchent à vendre leurs items au meilleur prix possible.

En somme, l'API de Wakfting joue un rôle crucial dans le bon fonctionnement de l'application. Elle facilite la gestion de l'inventaire, la mise à jour des prix, et bien plus encore, tout en assurant une expérience utilisateur fluide et agréable.

## Application Desktop

Bien qu'elle ne soit pas encore développée, l'application de bureau de Wakfting promet d'apporter une nouvelle dimension à votre expérience de jeu. Cette application sera capable de lire les fichiers de logs du jeu, de les analyser et de faire remonter les informations dans la base de données en fonction du client lié. Cela permettra une synchronisation presque instantanée entre votre jeu et l'application Wakfting, garantissant que vos informations sont toujours à jour.

Une des principales fonctionnalités de cette application de bureau sera le système de notifications. Lorsqu'un craft sera terminé, une notification apparaitra sur votre bureau. Cela vous permettra de rester informé de l'état de vos crafts, même lorsque vous n'êtes pas directement en train de jouer au jeu. Cette fonctionnalité vise à augmenter votre efficacité et à vous permettre de maximiser votre temps de jeu.

La combinaison de l'analyse des fichiers de logs et du système de notifications transformera votre manière de gérer vos crafts. Vous n'aurez plus à vérifier constamment l'état de vos crafts, car l'application de bureau le fera pour vous. Cela vous permettra de vous concentrer sur d'autres aspects du jeu, tout en sachant que vos crafts sont gérés efficacement.

En somme, l'application de bureau de Wakfting apportera une plus grande simplicité et une meilleure gestion de vos crafts dans Wakfu. Restez à l'écoute pour les futures mises à jour concernant le développement de cette application.

## Lier l'application à l'application de bureau

Pour lier votre compte Wakfting à l'application de bureau, nous avons allons mettre place un système simple et sécurisé basé sur un QR code. Ce système permet d'établir une connexion directe entre l'application mobile et l'application de bureau, assurant ainsi une synchronisation rapide et efficace des données.

La première étape consiste à générer un QR code sur l'application de bureau. Une fois que le QR code est généré, il suffit d'ouvrir l'application mobile et de scanner le QR code avec l'appareil photo de votre téléphone. Ce processus établit une connexion en socket entre l'application mobile et l'application de bureau, permettant à l'application mobile d'envoyer son identifiant unique à l'application de bureau.

Une fois que l'identifiant unique a été envoyé et reconnu par l'application de bureau, vos données peuvent être liées à votre compte. Cela signifie que toutes les informations de votre compte, y compris votre inventaire, vos crafts et votre suivi des prix, seront synchronisées entre les deux applications. Cela vous permet de gérer vos activités dans le jeu de manière plus efficace, que vous soyez sur votre téléphone ou sur votre ordinateur.

Il est important de noter que tout au long de ce processus, la sécurité et la confidentialité de vos informations sont notre priorité absolue. Aucune de vos informations personnelles n'est partagée ou stockée à l'extérieur de votre compte, et la connexion en socket est sécurisée pour garantir que vos données restent privées et protégées.

En somme, lier votre compte Wakfting à l'application de bureau est un processus simple mais puissant qui vous permet de maximiser votre expérience de jeu sur Wakfu. Restez à l'écoute pour plus d'informations sur les futures mises à jour et les améliorations de cette fonctionnalité.
