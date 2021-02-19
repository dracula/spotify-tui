### [Spotify TUI](https://github.com/Rigellute/spotify-tui)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning
the repo:

    $ git clone https://github.com/juanscr/dracula-spotify-tui

#### Install manually

Download using the [GitHub .zip
download](https://github.com/juanscr/dracula-spotify-tui/archive/master.zip)
option and unzip them.

#### Activating theme

1. Open the `dracula.yml` file in your favorite text editor and copy all the
   contents of the file.
2. Open the configuration file of `spotify-tui` located in
   `~/.config/spotify-tui/config.yml`. If this file does not exist, a sample
   configuration file can be found in [the Spotify TUI
   README](https://github.com/Rigellute/spotify-tui#configuration).
3. Lastly, replace all the `theme` section with the copied contents obtained in
   the `dracula.yml` file.

__Important__: Spotify TUI does not allow to change the background color of the
terminal. Therefore, for the complete Dracula color scheme the terminal must
already have the correct background set. The other colors are set correctly by
the configuration file.
