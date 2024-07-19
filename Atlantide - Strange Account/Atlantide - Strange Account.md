<!-- By mathys-lopinto -->
<h1 style="text-align: center;color: #ff0000;">Atlantide - Strange Account - 2024</h1>
<h2 style="text-align: center;color: #ff0000;">Part 1</h2>

# FR

## Description

Le crépuscule s abat sur la forêt lorsque votre regard est attiré par un éclat inhabituel. Niché entre les racines noueuses d un chêne centenaire, un fragment de papier jauni attire votre attention. Intrigué, vous vous en saisissez et découvrez un titre qui fait bondir votre cœur : L Atlantide a été retrouvée avec un lien amenant sur le dark web. Perplexe, vous scrutez les alentours. Comment un tel document a-t-il pu atterrir dans ces bois reculés ? Guidé par votre curiosité, vous vous empressez de consulter le lien. L article qui s affiche à l écran vous coupe le souffle. Les preuves présentées semblent irréfutables, les explications sur la dissimulation de cette découverte au grand public, terriblement plausibles. Pourtant, vous sentez intérieurement que quelque chose cloche. Est-ce une élaboration minutieuse d un canular ou la plus grande découverte de l histoire ? Déterminé à percer ce mystère, vous endossez le rôle de débunker. Armé de votre esprit critique et de votre soif de vérité, vous vous lancez dans une quête périlleuse. Vous décidez d abord de regarder le compte de la personne ayant posté l article. Il semblerait qu on puisse retrouver l endroit de la localisation de l Atlantide depuis le profil. ATTENTION : LE FLAG DOIT ÊTRE ENVOYÉ EN FRANÇAIS, SANS ACCENT NI MAJUSCULES. Par exemple, si la réponse est la mer Noire, le flag sera CAT{mer-noire}.

## Catégorie

Stéganographie

## Point et difficulté

9 points, moyen

## Fichier fournis

[profil-posteur-article-fr_en.md](https://github.com/mathys-lopinto/CatTheQuest2024_Write-Up/blob/main/Atlantide%20-%20Strange%20Account/profil-posteur-article-fr_en.md)

## Format du flag

``CAT{lieu-trouve}``

## Indice ajouté

Vous devez comprendre la signification de la description du profil

## Auteur

[mathys-lopinto](https://github.com/mathys-lopinto)

## Solution

Pour résoudre ce challenge, il faut tout d'abord comprendre la description du profil:
"Dans un monde composé de 7 continents, où la précision et la simplicité se rejoignent, une forme de mesure s'est imposée comme un pilier incontesté de la géolocalisation. Cette méthode, par sa clarté et sa facilité d'utilisation, guide nos pas avec une précision sans pareille. Elle nous permet de naviguer avec assurance à travers les méandres de notre monde complexe, nous offrant un repère fiable et univers3l. Sa simplicité apparente dissimule une puissance insoupçonnée, nous reliant de manière invisible mais indéniable à chaque coin de notre planète. En embrassant cette approche, nous célébrons l'ingéniosité humaine qui transcende les frontières physiques pour nous offrir un langage commun, une boussole numérique qui oriente nos vies et nos voyages vers de nouveaux horizons.

Psss: toi qui lis ma description, n'hésites pas à lire au-delà des lignes pour trouver la localisation de l'Atlantide."
> La description fait référence à la géolocalisation, plus précisément à la latitude et la longitude.

Ensuite, nous comprenons qu'il faut donc trouver une latitude et une longitude. Pour cela nous allons nous attarder sur la phrase "Psss: toi qui lis ma description, n'hésites pas à lire au-delà des lignes pour trouver la localisation de l'Atlantide.".

En récupérant tout les chiffres du profil, nous obtenons:

- 87 (email)
- 254 (likes)
- 98 (posts)
- 73 (description)
  - "composé de **7** continents"
  - "repère fiable et univers**3**l"

En combinant ces chiffres, nous obtenons la latitude et la longitude suivante: 87.254, 98.73.

Si nous tapons ces coordonnées sur [Google Maps](https://www.google.fr/maps/place/87%C2%B015'14.4%22N+98%C2%B043'48.0%22E/@84.9995834,98.7274251,17z/data=!3m1!4b1!4m4!3m3!8m2!3d87.254!4d98.73?entry=ttu), nous obtenons la localisation suivante: ``Océan Arctique``

Nous avons donc trouvée notre flag, et il ne reste plus qu'à l'envoyer en français, sans accent ni majuscules.

# EN

## Description

Twilight falls upon the forest when your attention is drawn to an unusual glint. Nestled between the gnarled roots of a centuries-old oak tree, a fragment of yellowed paper catches your eye. Intrigued, you pick it up and discover a headline that makes your heart leap: Atlantis Found with a link leading to the dark web. Perplexed, you scan your surroundings. How could such a document end up in this remote forest? Driven by curiosity, you hasten to follow the link. The article that appears on the screen takes your breath away. The evidence presented seems irrefutable, the explanations for the concealment of this discovery from the public, terribly plausible. Yet, you feel deep down that something is off. Is it an elaborate hoax or the greatest discovery in history? Determined to unravel this mystery, you take on the role of debunker. Armed with your critical thinking and thirst for truth, you embark on a perilous quest. You decide to first look at the account of the person who posted the article. It seems that the location of Atlantis can be found from the profile.WARNING: THE FLAG MUST BE SENT IN FRENCH, WITHOUT ANY ACCENT MARKS OR UPPER CASE. e. g If the answer is Black Sea the flag will be CAT{mer-noire}

## Category

Steganography

## Points and difficulty

9 points, medium

## Provided files

[profil-posteur-article-fr_en.md](https://github.com/mathys-lopinto/CatTheQuest2024_Write-Up/blob/main/Atlantide%20-%20Strange%20Account/profil-posteur-article-fr_en.md)

## Flag format

``CAT{lieu-trouve}``

## Added hint

You must understand the meaning of the profile description

## Author

[mathys-lopinto](https://github.com/mathys-lopinto)

## Solution

To solve this challenge, you must first understand the profile description:
"In a world made up of 7 continents, where precision and simplicity meet, one form of measurement has established itself as an undisputed pillar of geolocation. This method, with its clarity and ease of use, guides our steps with unparalleled precision. It allows us to navigate with confidence through the twists and turns of our complex world, providing us with a reliable and universal ref3rence point. Its apparent simplicity conceals an unsuspected power, linking us invisibly but undeniably to every corner of our planet. By embracing this approach, we celebrate the human ingenuity that transcends physical boundaries to give us a common language, a digital compass that guides our lives and journeys to new horizons.

Psss: you who read my description, feel free to read beyond the lines to find the location of Atlantis."
> The description refers to geolocation, more precisely to latitude and longitude.

Then, we understand that we must therefore find a latitude and a longitude. To do this, we will focus on the sentence "Psss: you who read my description, feel free to read beyond the lines to find the location of Atlantis.".

By retrieving all the numbers from the profile, we get:

- 87 (email)
- 254 (likes)
- 98 (posts)
- 73 (description)
  - "made up of **7** continents"
  - "universal ref**3**rence point"
  
By combining these numbers, we get the following latitude and longitude: 87.254, 98.73.

If we type these coordinates on [Google Maps](https://www.google.fr/maps/place/87%C2%B015'14.4%22N+98%C2%B043'48.0%22E/@84.9995834,98.7274251,17z/data=!3m1!4b1!4m4!3m3!8m2!3d87.254!4d98.73?entry=ttu), we get the following location: ``Arctic Ocean``

We have therefore found our flag, and all that remains is to send it in French, without any accent marks or upper case.

# Flag

``CAT{ocean-arctique}``

# Licence
 <p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt=""></a></p> 