# Gravitation

## English
I'm developing a video-game playable in web browsers on all kind of devices, desktops, tablets and smartphones.
Gameplay-wise, it's about controlling a spaceship in a 2D environment. The ship suffers from **Gravity**. The player is able to rotate the spaceship, to thrust it forward and to fire weapons.

There will be different game modes. An **Adventure** mode, playable offline in **Solo** telling the story of a lost spaceship trying to find its way back to civilization. The other Solo mode is a **Race** against the clock in levels varying from the Adventure mode.

Other game modes are **Multiplayer** modes. There is two groups of multiplayer modes, the one versus one mode is called **Duel** and the 1 to 4 player mode is called **Arena**. In both of them, you can play some **Race** in the same levels as the Solo mode Race or you can **Battle** in some new levels where the goals is only to kill your opponent(s).

Apart from the game itself, the user can create an account where he'll be able to configure the key mapping, retrieve is progression, add friends, invite them in a lobby and see is own rank in the world **Ladder**.

## Français
Je suis en train de développer un jeu-vidéo jouable dans les navigateurs web récents et ce, sur tout types d'appareil, ordinateur de bureau, tablettes et smartphones.

En ce qui concerne l'expérience de jeu, le joueur controllera un vaisseau spatial dans un environnement 2D. Ce vaisseau subira la **Gravité**. Le joueur sera capable d'orienter le vaisseau, de le faire avancer dans la direction vers laquelle il pointe. Il sera également capable de tirer différentes munitions.

Il y aura différents mode de jeu. le mode **Aventure**, jouable hors ligne en **Solo** raconte l'histoire d'un vaisseau perdu cherchant à reprendre contact avec la civilisation. L'autre mode **Solo** est un mode de course **contre-la-montre** dans des niveau dérivé de ceux du mode aventure.

D'autre mode de jeu **Multijoueur** seront disponible. le mode multijoueur en un contre un s'appellera **Duel** et le mode de 3 ou 4 joueurs s'appellera **Arène**. Dans chacun d'eux, il sera possible de faire des **Courses** à plusieurs dans les mêmes niveau que le **Contre-la-Montre**. Il sera également possible de faire des **Batailles** dans des niveaux spéciaux ou le seul but du jeu et de tuer ses ennemis.

En dehors du jeu, l'utilisateur pourra créer un compte ou il sera capable de configurer les touches du jeu, enregistrer sa progression, ajouter des amis, les inviter dans un **Lobby** et voir son **Classement** mondial.


Message to slack :

Bonjour, je suis en train de dev un jeu multijoueur avec Phaser.
Je veux utiliser node.js et socket.io pour le temps réel.
Petit problem, j'ai dev un premier POC en l'utilisant et le résultat n'est pas fameux.
Problème de latence etc...
Je me suis renseigné un peu sur l'interpolation et la prediction pour essayer de regler un peu ces problemes, par le biais de ce tuto =>
http://buildnewgames.com/real-time-multiplayer/ ( certe un peu vieux ).
J'ai cloner le Repo de Demo, mais le résultat est quelque peu décevant!
J'ai pensé que ca venait du fait d'etre en localhost, donc je l'ai mis sur Heroku => https://socket-io-test-rqm.herokuapp.com/
mais ce n'est pas beaucoup mieux.
Ma question est : Avez vous deja utilisez socket.io pour du multiplayer nécessitant une grande précision? et comment qu'on fait pour que sa marche bien ?
Merci d'avance :):):)
