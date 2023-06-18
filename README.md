Just a little script that downloads every single repository you have access to on Github and saves it on your server every day.

## Setup

1. Generate new github api personal access token (set expiration as you wish)
2. Copy the script on your server (`scp`) and make sure it's runable (`chmod`)
3. Add the following cron to your jobs `0 0 * * * root GITHUB_API_TOKEN=<INSERT_YOUR_API_PERSONAL_ACCESS_TOKEN> /path/to/the/script.sh >> /path/to/the/log.txt`
