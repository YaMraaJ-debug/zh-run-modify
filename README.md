# Deploy to HEROKU

**Important Note**
1. Upload all of your private files here: `config.env`, `token.pickle`, `rcl.conf`, `accounts.zip`, `shorteners.txt` etc...

**Mandatory Veriables in Config**

- `UPSTREAM_REPO`: Your github repository link, if your repo is private add `https://<deploy_token>:<empty_password>@gitlab.com/<your_username>/<repository_name>
` format. `Str`.
- `UPSTREAM_BRANCH`: Upstream branch for update. Default is `main`. `Str`

- `BOT_TOKEN`: The Telegram Bot Token that you got from [BotFather](https://t.me/BotFather). `Str`
- `OWNER_ID`: The Telegram User ID (not username) of the Owner of the bot. `Int`
- `TELEGRAM_API`: This is to authenticate your Telegram account for downloading Telegram files. You can get this from <https://my.telegram.org>. `Int`
- `TELEGRAM_HASH`: This is to authenticate your Telegram account for downloading Telegram files. You can get this from <https://my.telegram.org>. `Str`

- `BASE_URL`: Valid BASE URL where the bot is deployed to use torrent web files selection. Format of URL should be `https://app-name.herokuapp.com/`, where `app-name` is the name of your heroku app. `Str`
- `TORRENT_TIMEOUT`: Timeout of dead torrents downloading with qBittorrent and Aria2c in seconds. `Int`

------

## Deploy using CLI

- Deployment instructions uploaded [HERE](https://graph.org/Install-CLI-using-official-docs-httpsdevcenterherokucomarticlesheroku-cli-07-31)
- Carefully copy-paste every CMD one by one. If you miss maybe your BOT will not run.
