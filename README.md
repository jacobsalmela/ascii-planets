<p align="center">
  <strong>ASCII Planets</strong> is a spacefaring expansion to ASCII Empires (a "roll-and-write" board game of civilization building for 1-7 players)
  <br>
  <img src="https://user-images.githubusercontent.com/3843505/94575720-26f6cf80-023a-11eb-9fdf-15091fc5c396.png" alt="ascii-planets-sheet">
</p>

## Game Files

You can download pre-made game files [here](https://github.com/jacobsalmela/ascii-planets/releases), just print and _play_ (color and grayscale versions available).

GitHub Actions will auto-build the PDFs, but if you want to generate your own files using XeLaTeX, you can do so like this:

```
git clone https://github.com/jacobsalmela/ascii-planets.git
cd ascii-planets
xelatex rules.tex
xelatex planet_sheet.tex
```

### Feedback On The Game
Just create a new issue here on GitHub by [filling out the template](https://github.com/jacobsalmela/ascii-planets/issues/new?template=feedback.md).  Feel free to add additional comments as necessary.  You can also add feedback on Board Game Geek.

### Customizing Your Game

You can customize your game by changing a few lines of code.  Modify the colors or create your own planet layouts!  Check out [the wiki](https://github.com/jacobsalmela/ascii-planets/wiki) for more info.

## Background

[ASCII Empires](https://boardgamegeek.com/boardgame/307670/ascii-empires) won Board Game Geek's [2019's Roll-and-write contest](https://boardgamegeek.com/thread/2153371/roll-write-game-design-contest).  I enjoyed it so much but wanted it to have a sci-fi theme.  Thus, ASCII Planets was born.

## How To Play
The rulebook is included on the [Releases page](https://github.com/jacobsalmela/ascii-planets/releases).

# Contributing
Contributions and pull requests are welcome!  Make your own branch and GitHub actions should auto-build your PDFs whenever you push code.  This is useful if you don't have your own LaTeX environment setup.
