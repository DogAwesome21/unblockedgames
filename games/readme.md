# Games Folder

This folder contains all the individual games for the Games Hub project. Each game is stored in its own subfolder with an `index.html` file and any required assets.

## Structure Example

```
games/
  snake/
    index.html
    script.js
    style.css
  leveldevil/
    index.html
    assets/
```

## Adding New Games

1. Create a new folder inside `games/` with a unique name for your game.
2. Include an `index.html` file as the entry point.
3. Add any additional assets (images, scripts, sounds) inside the folder.
4. Update the main `index.html` to add a card pointing to your new game's `index.html`.
