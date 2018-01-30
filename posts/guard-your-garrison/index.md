# Guard Your Garrison

<video width="500" height="280" preload poster="https://github.com/franvarney/franvarney.github.io/blob/master/media/guard_your_garrison.png?raw=true">
  <source src="https://github.com/franvarney/franvarney.github.io/blob/master/media/guard_your_garrison.mp4"></source>
  <source src="https://github.com/franvarney/franvarney.github.io/blob/master/media/guard_your_garrison.webm?raw=true"></source>
</video>

Here is a game that I made to learn Unity and more about game development in general. Guard Your Garrison is strongly inspired by (read: a clone) Defend Your Castle, which was a Flash game I used to play in middle school. [XGen Studios](http://www.xgenstudios.com/) is actually still working on this game after all this time.

Besides growing up playing this game, I felt Defend Your Castle was a reasonable game to clone scope-wise and would help me focus on how to actually make games while also being able to complete the project. Having some C# experience and using Unity really made this a lot easier, but of course, a lot of research had to be done on things like quaternions and colliders and kinematics.

Play the game [here!](https://franvarney.github.io/games/guard-your-garrison)

### What I Learned

- Game development is really hard! Even for small games like this. Having engines and tools or an established series might alleviate a portion of the difficulty (but then there are probably more people on the team to deal with as well). I have newfound respect for people that work on games.
- Bugs feel never ending, holy heck. I keep thinking I worked everything out, only to discover more bugs while making a video for this post.
- Tweaking currency, points, spawn rates, and upgrades took a lot of finagling. For the sake of simplicity as this was my first game, I kept upgrades simple and only guaranteed the game is playable to ~15 levels.
- Feedback and criticism hurts. More than I ever felt doing photography. And it's also hard to get things "right" the first time without data or research. And then you have to consider what you want to get out of it. And you have to decide what's more important. And then....well, there's just a lot going on.
- Binding a button with two separate methods (`Button.onClick.AddListener`) will crash the game on Windows but not in a WebGL version of the game. I did this on accident and it took a while to realize I assigned the same button to two different variables through the Unity inspector. Oops.

#### Assets

- [5 RPG Characters - Evil](https://assetstore.unity.com/packages/2d/characters/5-rgp-characters-evil-96737)  by HQ Game Assets
- [2D Cartoon Castles](https://assetstore.unity.com/packages/2d/environments/2d-cartoon-castles-42750) by QotoQot
- [Tower 2D Sprite Pack](https://assetstore.unity.com/packages/2d/environments/tower-2d-sprite-pack-71771) by StetsRoman
- [2D Sky](https://assetstore.unity.com/packages/tools/particles-effects/2d-sky-free-21555)  by G.E.TeamDev
- [Toon FX](https://assetstore.unity.com/packages/vfx/particles/toon-fx-25601) by Kenneth "Archanor" Foldal Moe
- [Luckiest Guy Font](https://fonts.google.com/specimen/Luckiest+Guy)
- UI designed by me and my boyfriend, made by me
