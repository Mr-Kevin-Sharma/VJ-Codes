━━━━━━━━━━━━━━━━━━━━

<h2 align="center">
    ──「 ғɪʟᴇ sᴛᴏʀᴇ ᴘʀᴏ 」──
</h2>

<p align="center">
  <img src="https://files.catbox.moe/jsiael.jpg" alt="Bot Banner">
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=FILE+SHARING+!;CREATED+BY+CODEFLIX+DEVELOPER!;A+ADVANCE+BOT+WITH+COOL+FEATURE!" alt="Typing SVG">
</p>

━━━━━━━━━━━━━━━━━━━━

<details><summary><b>ғᴇᴀᴛᴜʀᴇs:</b></summary>

- <b>Batch & Custom Batch Links:</b> Create links for one or multiple posts using <code>/batch</code> & <code>/custom_batch</code>  
- <b>Link Generator:</b> Instantly generate direct links with <code>/genlink</code>  
- <b>Broadcast Tools:</b> Send messages or media to all users using <code>/broadcast</code>, <code>/dbroadcast</code>, or <code>/pbroadcast</code>  
- <b>Auto File Deletion:</b> Control auto-delete with <code>/dlt_time</code> & <code>/check_dlt_time</code>  
- <b>User Management:</b> Ban/unban users and view banlist via <code>/ban</code>, <code>/unban</code>, and <code>/banlist</code>  
- <b>Multi Force Subscription:</b> Manage multiple Force Sub channels with <code>/addchnl</code>, <code>/delchnl</code>, <code>/listchnl</code>  
- <b>Admin Control:</b> Add/remove admins with <code>/add_admin</code>, <code>/deladmin</code>, and list them via <code>/admins</code>  
- <b>Bot Analytics:</b> Get uptime stats with <code>/stats</code>, user info with <code>/users</code>, and DB count via <code>/count</code>  
- <b>Deployment Ready:</b> Deploy quickly on <b>Heroku</b>, <b>Koyeb</b>, <b>Render</b>, or <b>Railway</b>

<b>✨ More features & enhancements coming soon...</b>

</details>

<details><summary><b>ᴠᴀʀɪᴀʙʟᴇs:</b></summary>

### Required Environment Variables

- `API_HASH` → Get from [my.telegram.org](https://my.telegram.org)
- `APP_ID` → Get from [my.telegram.org](https://my.telegram.org)
- `TG_BOT_TOKEN` → From @BotFather
- `OWNER_ID` → Your Telegram user ID
- `CHANNEL_ID` → Your Telegram Channel ID (e.g., `-100xxxxxxxxxx`)
- `DATABASE_URL` → Your MongoDB URL
- `DATABASE_NAME` → MongoDB database name

### Optional Variables

- `ADMINS` → Space-separated list of admin user IDs
- `START_MESSAGE` → Custom welcome message (supports HTML)
- `PROTECT_CONTENT` → `True` to prevent forwarding of sent files

</details>

---

## 🔧 Commands

/start - Start the bot or get posts
/batch - Create link for multiple posts
/custom_batch - Create custom batch from channel/group
/genlink - Generate link for a single post
/users - View bot statistics
/broadcast - Broadcast message to all users
/dbroadcast - Broadcast with auto-delete
/pbroadcast - Pin broadcast to all users
/stats - Check bot uptime
/dlt_time - Set file auto-delete time
/check_dlt_time - Check current auto-delete time
/ban - Ban a user
/unban - Unban a user
/banlist - View all banned users
/addchnl - Add Force Sub channel
/delchnl - Delete Force Sub channel
/listchnl - View Force Sub channels
/fsub_mode - Toggle Force Subscribe feature
/add_admin - Add new admin
/deladmin - Remove an admin
/admins - List all current admins


<p align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="Divider">
</p>

---

## 🧪 Other Branches

- [ᴛᴏᴋᴇɴ](https://github.com/Codeflix-Bots/FileStore/tree/token)
- [sʜᴏʀᴛɴᴇʀ](https://github.com/Codeflix-Bots/FileStore/tree/Shortner)

---

## 🚀 Deployment Methods

<details><summary><b>Deploy Options</b></summary>

### 🚀 Deploy on Heroku

<p align="center">
  <a href="https://heroku.com/deploy?template=https://github.com/Codeflix-Bots/FileStore">
    <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy On Heroku">
  </a>
</p>

### 🚀 Deploy on Koyeb

<p align="center">
  <a href="https://app.koyeb.com/deploy?type=git&repository=github.com/Codeflix-Bots/FileStore&branch=master&name=master">
    <img src="https://www.koyeb.com/static/images/deploy/button.svg" alt="Deploy On Koyeb">
  </a>
</p>

### 🚀 Deploy on Railway

<p align="center">
  <a href="https://railway.app/deploy?template=https://github.com/Codeflix-Bots/FileStore">
    <img height="45px" src="https://railway.app/button.svg" alt="Deploy on Railway">
  </a>
</p>

### 🚀 Deploy on Render

<p align="center">
  <a href="https://render.com/deploy?repo=https://github.com/Codeflix-Bots/FileStore">
    <img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render">
  </a>
</p>

### 🖥️ Deploy on VPS

```bash
git clone https://github.com/Codeflix-Bots/FileStore
cd FileStore
pip3 install -U -r requirements.txt
# Edit info.py with your variables
python3 bot.py
