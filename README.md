![Moonrise logo](docs/media/favicon.ico) 

# Moonrise

A simple, lightweight, responsive landing page template for a Minecraft server. Integrates with Discord, Minecraft server status, and GitHub Pages to host a free website.

Features:
- Shows the server's Minecraft Java version automatically
- Shows a channel from your Discord server on the homepage
- Changes color when Minecraft server is detected to be offline
- Click to copy server IP
- Screenshots page
- Progressive Web App (coming soon)

<br />

[![Support Discord](https://img.shields.io/badge/Support%20Discord-▸-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://coffeebank.github.io/discord)

Demo: https://coffeebank.github.io/moonrise

![CrispBuild demo](docs/media/demo01.jpg)

## Getting Started

The quickest way to get up and running is to use GitHub Pages (free).

1. Click "Fork" on the top right corner
1. Invite [Widgetbot](https://widgetbot.io) into your Discord server, and [get your Server ID and Channel ID](https://www.youtube.com/watch?v=6dqYctHmazc) to show on your website
1. Edit `_config.yml` with your information, using `media` folder for logos/assets
1. Edit `index.md`, `about.md`, `map.md`, and `donate.md` with your info
1. Screenshots page will autofill with pics in the `screenshots` folder

Finally, you're ready to publish your site:
1. Click the "Settings" tab
1. Change the `Repository name` to the website link you want
1. On the left sidebar, click "Pages", Source: `master` branch, `/docs` folder, click "Save"

And you're done! Your website will be live at: `https://<username>.github.io/<repositoryname>`

[Wiki: For advanced users, site navigation, and other features >](https://github.com/coffeebank/moonrise/wiki)

## Updates

To get new moonrise updates synced to your website, go to your repo, and click "Fetch upstream", then "Fetch and merge".


## License

See [LICENSE](LICENSE.md).

Contributions are welcome, with all code falling under this LICENSE.


## Attributions

#### Services
- https://api.mcsrvstat.us/
- https://widgetbot.io/