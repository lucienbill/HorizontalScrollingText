# EN : HorizontalScrollingText
Do you watch the news?
Picture the text on the lower portion of the screen : some "flash news" scroll all the time.
I wanted to have that on my live stream on Twitch, so I codded this simple thing.

Largely inspired from [this code](https://dev.to/techthor/pure-css-continuous-horizontal-text-scroll-42a3).

## How to use it in OBS?
Just clone this repo, and include "newsbanner.html" as a browser source : 
1. Clone this projet or [download the latest release](https://github.com/lucienbill/HorizontalScrollingText/releases) on your computer (example: `C:/somefolder/stream`)
2. In OBS, create a new "Browser" source, and enter the path to the HTML file (example: `C:/somefolder/stream/newsbanner.html`)
3. Place your source in the appropriate location.
4. Customize everything (the colors, the messages, ...)

Change the speed, the text, the style however you like.
You can also set the value `doRandomize` to `true` (in `newsbanner.html`) if you want your newsbits to be reordered at random.

Here is a heavily compressed gif to show how I do it:

![](https://raw.githubusercontent.com/lucienbill/HorizontalScrollingText/main/Documentation/newsbanner-compressed.gif)

## I have a question!
Sure, just ask me on [twitter](https://twitter.com/BillyTheTroll) or create an [issue](https://github.com/lucienbill/HorizontalScrollingText/issues) ;)

# FR : Texte qui défile horizontalement
Regardez-vous les infos ?
Visualisez le texte en bas de l'écran : des brèves défillent en permanence.
Je voulais avoir la même chose sur mon stream Twitch, donc j'ai codé ce truc simple.

Largement inspiré de [ce code](https://dev.to/techthor/pure-css-continuous-horizontal-text-scroll-42a3).

## Comment l'utiliser dans OBS ?
Clonez ce repo, et ajoutez le fichier "newsbanner.html" comme source navigateur dans OBS : 

1. Clonez ce projet ou [téléchargez la release la plus récente](https://github.com/lucienbill/HorizontalScrollingText/releases)  sur votre ordinateur (exemple: `C:/somefolder/stream`)
2. dans OBS, créez une source de type "navigateur" et entrez le chemin du fichier HTML (exemple: `C:/somefolder/stream/newsbanner.html`)
3. Placez la source à l'endroit qui convient le mieux.
4. Customisez tout (les couleurs, les messages, ...)

Changez la vitesse, le texte et le style à votre guise.
Vous pouvez aussi mettre la valeur `doRandomize` à `true` (dans `newsbanner.html`) si vous voulez réordonner de manière aléatoire vos bouts de news.

Voici un gif très compressé qui montre comment faire :

![](https://raw.githubusercontent.com/lucienbill/HorizontalScrollingText/main/Documentation/newsbanner-compressed.gif)

## J'ai une question !
Allez, posez-la moi sur [twitter](https://twitter.com/BillyTheTroll) ou créez une [issue](https://github.com/lucienbill/HorizontalScrollingText/issues) ;)
