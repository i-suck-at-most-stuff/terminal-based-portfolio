
# Terminal Portfolio

This is a terminal-inspired portfolio project that showcases various features, including a terminal interface, custom commands, and integration with external APIs, such as Spotify for the current song playing.

## Features

- **Spotify Command**: Displays the currently playing song from your Spotify account.
- **Weezer Command**: Plays the iconic Buddy Holly riff by Weezer.
- **Help Command**: Lists all available commands in the terminal.
- **Custom Commands**: Includes personal commands for links to my portfolio, Hack Club, and more.
- **Responsive Design**: Terminal works on both desktop and mobile with a special notification for mobile users.
- **GitHub Push Command**: Displays recent commit messages from a GitHub repository.

## Setup

Since this project is hosted on GitHub Pages, you don't need to install anything locally. You can simply visit the deployed version of the site to interact with the terminal interface.

## Commands

Here is a list of the available commands in the terminal:

### `help`
Displays a list of all available commands.

### `about`
Shows links to my portfolio and Hack Club.

### `clear`
Clears the terminal output.

### `spotify`
Shows the currently playing song from your Spotify account, or informs you if nothing is currently playing.

### `weezer`
Plays the Buddy Holly riff by Weezer.

### `github`
Displays recent commit messages from your GitHub repository.

## Contributing

Feel free to fork this project, make improvements, and submit pull requests. If you'd like to suggest new features or report bugs, open an issue in the GitHub repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Customization

You can add new commands by expanding the `commands` object in the `JavaScript` code. Each command can either return a predefined message or execute an asynchronous function (e.g., fetch data from an API or play a sound file).
