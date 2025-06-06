📞 Contact

> [Termux guides if you run on mobile](https://github.com/MeoMunDep/Guides-for-using-my-script-on-termux)


> If you encounter any issues or have questions, feel free to reach out:

- Contact: [Link](t.me/MeoMunDep)
- Group: [Link](t.me/KeoAirDropFreeNe)
- Channel: [Link](t.me/KeoAirDropFreeNee)

> > > Help me with your referral [Link](https://t.me/HamsterdamPlayBot/game?startapp=146184)

## 🚀 Getting Started

> Remember to download Nodejs version: **22.11.0** and NPM version: **10.9.0**


To get started with the bot, follow these steps:

0. **Dowload NodeJS to run the bot**

-> Double click on setup.bat or setup.sh if you want to run automatically, remember to fill all the necessary data.


-> [Link](https://t.me/KeoAirDropFreeNe/257/1462)

1. **Install Dependencies and Modules:**

   ```
   npm i user-agents cloudscraper axios meo-forkcy-colors meo-forkcy-utils p-limit https-proxy-agent socks-proxy-agent 
   ```

2. **Prepare Configuration Files:**

   > You'll need to set up a few configuration files for the bot to work properly.

## 📁 Configuration Files

### 1. `configs.json` 📜 - Adjust configuration

```json
{
  {
  "howMany2048Games": 10,
  "isSpin": true,
  "isDoTasks": true,
  "isBuyHamsters": true,
  "isClaimAchievements": true,
  "delayEachAccount": [5, 8],
  "limit": 5, //number of accounts run in a row
  "countdown": 300, //time to restarts all the accounts - count by seconds
}
```

### 2. `datas.txt` 🗂️ -  Get it from here >>> [Link](https://t.me/KeoAirDropFreeNe/257/6879)

```txt
query_id.../user...
query_id.../user...
query_id.../user...
```

### 3. `wallets.txt` 💼 - Cannot update yet.

```txt - wallet address
abc...xyz
abc...xyz
abc...xyz
```

### 4. `proxies.txt` 🌐 - Proxy is an option. If you have one, fill it in; otherwise, leave it blank.

```txt
http://user:password@host:port
https://user:password@host:port
socks4://user:password@host:port
socks5://user:password@host:port
```

💡 Usage:

> You need to `cd` to the file after extract it
> To run the bot, use the following command: `cd hamsterdam; node meomundep`

🎇Enjoy!
