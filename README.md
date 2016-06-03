# Slackwolf
Slackwolf is a bot for Slack. After inviting the bot to a channel, you can play the timeless game of [Werewolf (also called Mafia)](https://en.wikipedia.org/wiki/Mafia_(party_game)).

![ProjectImage](http://i.imgur.com/0Kwd8oe.png)

## Roles
Slackwolf currently supports Seer, Bodyguard, Lycan, Tanner, Beholder, Villager, Wolfman, and Werewolf. You'll need at least a 6 player game in order to see roles other than Seer/Villager/Werewolf given out.

## How to play
`/invite` the bot and type !help

## Installation
Slackwolf requires PHP 5.5+ and [Composer](https://getcomposer.org/).

```
git clone http://github.com/chrisgillis/slackwolf
cd slackwolf
composer install
```

Edit the `.env` file with a valid real-time messaging bot token from Slack. Get a valid token from the "Custom Integrations" tab of your Slack "Configure Apps" page. Also be sure to put the correct bot name in the `.env` file as well.

To start the bot type `php bot.php`

## Contributing

Send in pull requests. I wrote this very quickly and it could use some major refactoring of its components. It also needs a lot more roles.

## License

MIT License.
