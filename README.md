# Face-Recognition-Project

La reconnaissance facile consiste à reconnaitre une personne sur une image ou une 
vidéo. Elle se déroule en trois temps : la détection de visage afin de repérer le visage, 
l’analyse du visage qui donne un résultat numérique, et enfin la reconnaissance qui 
compare ce résultat avec la base de données. Elle nécessite donc une base de données 
de visages enregistrés.
D’abord utilisée comme outil de surveillance et de sécurité, elle a vu, ces dernières 
années, ses usages se développer dans la sphère publique comme privée. Ainsi son 
utilisation est de plus en plus fréquente et dans de nombreux domaines. Elle est 
employée en robotique, en biométrie, pour la sécurité grâce aux vidéos de 
surveillances, sur les réseaux sociaux (comme avec le projet DeepFace de Facebook), 
afin de déverrouiller des objets électroniques ou même des domiciles, effectuer des 
paiements, trier des photos, ou encore retrouver des membres de sa famille à l’aide 
d’une simple photo. Il y a d’autres usages moins communs, comme l’aide aux 
aveugles et aux personnes souffrant de prosopagnosie (trouble de l’identification ou de 
la mémorisation des visages humains), ou encore la détection des interdits de jeux dans 
les casinos.

Ce projet est dévisé en deux:

Dans la premiere partie, nous avons créé un réseau de neurones avec Keras à l'aide du 
backendTensorFlow pour classifier les chiffres manuscrits. Bien que nous ayons 
atteint une précision de 99%, il existe encore des possibilités d'amélioration. Nous 
avons également appris à classer les chiffres manuscrits personnalisés, qui ne faisaient 
pas partie du jeu de données de test.
l'utlisation des images manuscrites des chiffres à partir de la base de données MNIST 

La deuxième : FIND YOUR TWIN ou « trouve ton jumeau » est le nom de l’application que nous 
avons réalisé, elle consiste à trouver une célébrité qui ressemble à l’utilisateur. 
L’utilisateur va se trouver en premier lieu avec une interface qui va lui demander de 
prendre une photo, une fois cette opération est terminée, la photo prise sera transmise
comme paramètre à notre modèle déjà défini, qui va retourner une célébrité qui 
ressemble à l’utilisateur, et enfin une photo de cette célébrité sera affichée à 
l’utilisateur. 
Nous avons pu atteindre une exactitude (Accuracy) de 0.8655 par le modèle MobilenetV2.
