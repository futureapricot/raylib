<p align="middle">
  <img src="https://github.com/raysan5/raylib/blob/master/logo/raylib_logo_animation.gif" height="300px" />
  <img src="https://www.haremonic.games/assets/poster.1392b291.png" height="300px" /> 
</p>


This is a Striped-down and Modified version of [Raylib](https://github.com/raysan5/raylib) to use exclusively with Hare136: Slider

---

The pipeline to work with this is:

1. First, in [futureapricot:raylib](https://github.com/futureapricot/raylib)  
   1. Pull latest master  
   2. Merge/Rebase in hare-lib  
   3. Clean and strip-down in hare-lib  
2. Second, in [autopawn/hare136-slider](https://github.com/autopawn/hare136-slider)  
   1. git subrepo pull libs/raylib --force