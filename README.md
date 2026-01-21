# cub3D - my raycaster project

hey, this is my cub3d project for 1337 school. basically its a game like wolfenstein 3d where i used raycasting to make a 3d view from a 2d map. i worked hard on it so hope you like it.

## features

i did the mandatory part but i also added the **Bonus** features because i wanted to get the full score.

here is what works:
- 3d walls rendering
- texturs on the walls
- floor and ceilling colors
- map parsing (it checks for errors so dont try to crash it with bad maps)

### the bonus part:
- **mini map**: you can see the map in the corner and the player moving
- **mouse rotation**: you can look arround with the mouse not just arrows
- **doors**: i added doors that you can open and close
- **animations**: i have an aim sprite that is animated
- **collision**: you cant walk throgh the walls

## how to run it

first you need to have `make` and `gcc` installed.

1. clone the repo
2. compile everything with make:
```bash
make
```
3. run the game with a map:
```bash
./cub3D maps/good/works.cub
```
you can find other maps in the `maps/good` folder. i also put some bad maps in `maps/bad` to test the error handling but they just exit the program with error message.

controls

- W, A, S, D: move the player
 
- left / right arrows: rotate camera
 
- Mouse: rotate camera (bonus)

- Mouse: right click (bonus)
 
- ESC: quit the game
 
- red X button: also quits the game
