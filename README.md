Peli on harjoitus työ Unreal Engine versiolla 5.2 
peli projecti sisältää suurimmaksi osaksi blueprints mutta muutama yksi c++ scipt löytyy.
Projectin blueprintin ovat commentoitu kertomaan ja selittämään mitä mikäkin tekee sekä helposti muokattavissa oman mielen mukaan.
projecti on helposti suoraan importattavissa kaikki löytyy tästä git reposta.
Tärkeä lataa 5.2 unreal engine ohjeet lataa zip extract file  avaa shooter tiedotto (unreal engine  project) mahdollisesti joudut buildaamaan tiedoston tiedosto aukeaa.
peli projectin ominaisuudet 
                    Hud
-Main menu(pelaaja voi quit tai Aloittaa pelin)
Dead Menu( tämä tulee kun pelaaja kuolee 3 kertaa tästä on mahdollista mennä takaisin mainmenu tai resettaa peli)
BatleHud ( tästä löyttyy pelaajalle tiedot hp määrä, elämä pisteet, score joka päivittyy tuhottujen vihollisten mukaan)
                  BluePrints
-Enemy Character (joka seuraa sekä vahinkoittaa pelaajaa)
-pelaaja character (joka voi tehdä vahinkoa viholliseen sekä liikku alueella)
-Weapon (Pelaajan Weapon joka anttaa mahdollisen ampua)
-Projectile ( kaikki tiedot weaponista tuleville bulleteille)
-EnemyAi (Rajaa enemyn Ai liikkuvuuden)
-EnemySpawn( spawn enemyn)
-Explosion ( enemy kuoltu tekee räjähtys particelin)
-IDamage( jakaa damage tidon muihin blueprinteihin)
-ShooterMode ( pelin Gamemode Tiedot)
-MainMenuGamemode ( pelin mainmenu Gamemode Tiedot
c++ 
-BaseCharacter (pelaajan perustoiminnot liikkuvuudet sekä hp tunnisteet)


