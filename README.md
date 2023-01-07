# Steam deck games fixes

[![image](https://user-images.githubusercontent.com/5399780/211128121-c51be3b6-3b02-4acb-8be6-2cb12afc00ea.png)
](https://github-com.translate.goog/eregnier/steam-deck-games-fixes?_x_tr_sl=auto&_x_tr_tl=de&_x_tr_hl=fr&_x_tr_pto=wapp)

[![image](https://user-images.githubusercontent.com/5399780/211128139-41f71c46-501b-4d4f-b7ab-77b2d628db14.png)
](https://github-com.translate.goog/eregnier/steam-deck-games-fixes?_x_tr_sl=auto&_x_tr_tl=zh-CN&_x_tr_hl=fr&_x_tr_pto=wapp)

 [![image](https://user-images.githubusercontent.com/5399780/211128163-2498e8e6-26f3-4036-a33f-2d1e28e37ed6.png)](https://github-com.translate.goog/eregnier/steam-deck-games-fixes?_x_tr_sl=auto&_x_tr_tl=fr&_x_tr_hl=fr&_x_tr_pto=wapp)

[![image](https://user-images.githubusercontent.com/5399780/211128182-714f9c8a-083f-47c3-83d2-ef1819c35cd7.png)
](https://github-com.translate.goog/eregnier/steam-deck-games-fixes?_x_tr_sl=auto&_x_tr_tl=es&_x_tr_hl=fr&_x_tr_pto=wapp)

[![image](https://user-images.githubusercontent.com/5399780/211128230-0a863e99-6a0e-4a7d-93c2-8aa42cc134f0.png)
](https://github.com/eregnier/steam-deck-games-fixes)

This is a wiki / documentation repository to reference all tips to make games work properly on steam decks

Please see [how to contribute](contribution.md) to add your own tricks to this guide

At the moment, this is a simple document where content will be added. Depending on contributions and community suggestions the form of this project may change, but the goal will remain the same : provide accurate and reproductible steps to fix games on steam deck.

The trick list might be long, you can use your browser search feature CTRL+F to find something quickly in this page.

### Celeste - Heroic launcher

[Source](https://www.youtube.com/watch?v=WGeHKRr0AmQ)

Problem :

 - The game displays a black screen

Solution : 

 - Add variable environement in game options in heroic launcher (see video) where variable name is `FNA3D_FORCE_DRIVER` and value is `OpenGL` (don't forget to click on + / add button)


### Sonic mania - Heroic launcher

[Source](https://www.reddit.com/r/SteamDeck/comments/upqirx/comment/i8mm3ys/?utm_source=share&utm_medium=web2x&context=3)

Problem : 

 - The game run in windowed mode. When I set full screen from option menu, then the game displays a black screen.

Solution :

 - When game is not running edit file located at `/home/deck/Games/Heroic/Prefixes/Sonic Mania/pfx/drive_c/users/steamuser/AppData/Local/Sega/SonicMania/Settings.ini`
replace `windowed=y` => `windowed=n` and `exclusiveFS=n` => `exclusiveFS=y` (this is a text file you can edit from steam deck desktop mode and just save once done)
