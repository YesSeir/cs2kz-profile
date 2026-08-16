### Installation
1. Go to your github repository and upload `index.html` and `icon.ico` files
2. Go to your repository `Settings - Pages`
3. Enable github pages
4. Install plugin `RecordsData`
5. Give access to repository `Profile - Settigs - Developer Settings - Personal access tokens - Fine-grained tokens - Generate new token`
6. Configuration path `game/csgo/cfg/plugins/RecordsData/config.json`
6. Configuration path `game/csgo/cfg/plugins/RecordsData/config.json`
7. First time use command `!sync` on server, and all your runs will on site
8. Site available by the way `https://yourname.github.io/reponame`

    ![alt text]({2EE7FEE5-0E8F-4603-A427-A8BF602F0937}.png)


### ⚙️ Configuration

```json
{
  "database_path": "csgo/addons/cs2kz/data/cs2kz.sqlite3", // default db path
  "github_repo": "yourname/reponame",  // example my repository here https://github.com/yourname/reponame
  "github_token": "github_pat_*****",  // place token here
  "records_path": "data/records.json", // dont change
  "players_path": "data/players.json"  // dont change
}
```
