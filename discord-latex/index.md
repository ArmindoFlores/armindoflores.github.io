# ![discord-latex-icon](https://i.imgur.com/nBHRGr8.png) discord-latex
A simple bot to render beautiful math formulas within discord using LaTeX. Consider supporting me and this project [here](https://ko-fi.com/armindoflores)!

## Usage
The first step is to add this bot to your server using [this link](https://discord.com/api/oauth2/authorize?client_id=837720764618244137&permissions=519232&scope=bot). Be sure to give it the required permissions!
After this, the bot will react to messages with the format 

    ```latex --flags
    some LaTeX code
    ```

and if you click on the white checkmark, it will reply with a rendered image, like so:

![reply-example](https://i.imgur.com/fQXULHo.png)

The currently supported flags are 
* __--bg-color=COLOR:__ Change the background color of the rendered image. Available colors are white (default), black and transparent.
* __--fg-color=COLOR:__ Change the foreground color of the rendered image. Available colors are black (default) and white.

The bot will also show you this information if you type `!help`.

## Configuration
Configuration is done via the `!config` command. So far, you can configure where the bot is allowed to send messages and what its prefix should be. 
To set a field, just navigate using the arrows to the correct page and then type the value you want to set it to.

![config-example1](https://i.imgur.com/2rAT4Wt.png)
![config-example1](https://i.imgur.com/1b5tJmL.png)

For the channel selection you can either type the channel name (or part of it) or copy the channel ID.
