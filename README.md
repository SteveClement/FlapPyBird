FlappyBirdClone
===============

A Flappy Bird Clone made using [python-pygame][1]

How-to
------

1. Install Python 2.7.X from [here](https://www.python.org/download/releases/)

2. Install PyGame 1.9.X from [here](http://www.pygame.org/download.shtml) or via pip from hg repository `pip install hg+http://bitbucket.org/pygame/pygame`

2.1 If on OSX install homebrew: ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
2.2 Install dependecies: brew install sdl sdl_image sdl_mixer sdl_sound sdl_ttf

3. Install virtualenv: pip install virtualenv

4. Clone this repository: `git clone https://github.com/SteveClement/FlapPyBird.git` or click `Download ZIP` in right panel and extract it.

5. Create virtualenv: cd FlapPyBird ; virtualenv -p python2 venv ; . venv/bin/activate ; pip install -r requirements.txt

6. Run `python flappy.py` from the repo's directory

7. use <kbd>&uarr;</kbd> or <kbd>Space</kbd> key to play and <kbd>Esc</kbd> to close the game.

  (Note: Install pyGame for same version python as above)

  (For x64 windows, get exe [here](http://www.lfd.uci.edu/~gohlke/pythonlibs/#pygame))

ScreenShot
----------

![Flappy Bird](screenshot1.png)

[1]: http://www.pygame.org
