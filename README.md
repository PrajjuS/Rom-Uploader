# Auto Rom Uploader
An Automated Script to upload rom builds to download server like sourceforge

## Instructions
### 1. Adding secrets
Go to your `repo settings > secrets > new repository secret` and add these secrets.
- `BOT_TOKEN`: Telegram bot token to notify in telegram
- `CHAT_ID`: Telegram group chat ID where you will be notified after uploading rom to dowload server
- `SERVER_ADDRESS`: Address of the download server
- `SERVER_PATH`: Path of the download server where build needs to be uploaded
- `SERVER_LINK`:  Link of the download server where build will be uploaded
- `SERVER_PASSWORD`: Password of the download server

### 2. Running workflow
- Go to your repo `Actions`
- Select `Rom Uploader` workflow
- Tap on `Run workflow`
- Enter your download link in `Download Link` section
- At last tap on `Run workflow` button

<details>
  <summary><h3>Secrets Example</h3></summary>

  - `BOT_TOKEN`: 123093634:2gABCbjqwolka5jn95gaklevn
  - `CHAT_ID`: -10012344567
  - `SERVER_ADDRESS`: prajjus@frs.sourceforge.net
  - `SERVER_PATH`: /home/frs/project/prajjus-roms/Project-Elixir-Vince
  - `SERVER_LINK`: https://sourceforge.net/projects/prajjus-roms/files/Project-Elixir-Vince
  - `SERVER_PASSWORD`: MeNoobKEK

</details>
