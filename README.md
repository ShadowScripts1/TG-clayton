[Click here to start](https://t.me/claytoncoinbot/game?startapp=6944804952)
---

# Clayton Bot

**Clayton Bot** is an automated tool designed to interact with the **Clayton Coin platform**. It can perform various tasks like daily check-ins, farming, partner tasks, and playing games to earn Clayton Coins (CL) and experience points (XP).

## Features

- **Automatic Login**
- **Daily Reward Claiming**
- **Farm Management**
- **Partner Task Completion**
- **Twitter Task Handling**
- **Bot Usage Task Completion**
- **Automated Game Playing**
- **Multi-Account Support**

---

## Prerequisites

Before you begin, make sure you have:

- **Node.js** installed
- Basic knowledge of **JavaScript** and **Node.js**

---

## Installation

Follow these instructions to set up the bot on Termux for Android:

### 1. Install Node.js and Git

Run these commands in Termux to install Node.js and Git:

```shell
pkg update && pkg upgrade
pkg install nodejs git
```

### 2. Clone the Repository

Clone the repository to your local machine with:

```shell
git clone https://github.com/ShadowScripts1/TG-clayton
```

### 3. Navigate to the Project Directory

```shell
cd TG-clayton
```

### 4. Install Dependencies

Install the required Node.js dependencies:

```shell
npm install
```

---

## Configuration

1. **Edit `data.txt`**  
   Open the `data.txt` file in the project root directory.
   
   - Add your Clayton Coin account information in this format, with each line representing a different account.
   
   Example of `data.txt`:
   ```
   query_id=123456 user_id=78910
   ```

2. **Enable Auto Features**  
   In `config.json`, you can enable or disable specific automated features by setting `"true"` or `"false"` for each task.

---

## Usage

To start the Clayton Bot, run the following command:

```shell
node main.js
```

The bot will automatically cycle through the accounts listed in `data.txt`, performing tasks and earning rewards.

---

## Error Codes

Here are some common error codes you might encounter:

- **`ECONNREFUSED`**: Connection refused; check server status or network.
- **`ETIMEDOUT`**: Connection timed out; check server response or network.
- **`401 Unauthorized`**: Credentials invalid or expired.
- **`403 Forbidden`**: Access denied; possible account issue.
- **`404 Not Found`**: Resource missing; check task parameters.
- **`409 Conflict`**: Conflict with server state; retry the action.
- **`500 Internal Server Error`**: Server error; try again later.

### Troubleshooting Tips

1. **Verify Account Information**: Double-check credentials in `data.txt`.
2. **Check Network**: Ensure your internet connection is stable.
3. **Server Status**: Verify that Clayton Coin servers are online.
4. **Retry**: Wait and try running the bot again if issues persist.

---

## Registration

If you don't have a Clayton Coin account, you can register using this link:

[Register for Clayton](https://t.me/claytoncoinbot/game?startapp=6944804952)

---

## Viewing Reports

To view a balance report, run:

```shell
node report.js
```

This will display the total balance across accounts.

---

## How to Get `tgWebAppData` (query_id / user_id)

1. **Login to Telegram** via web or desktop.
2. **Open DevTools** (press `F12`) and go to the **Console** tab.
3. Run the following command:

   ```javascript
   copy(Telegram.WebApp.initData)
   ```

4. Copy the output (e.g., `query_id=... / user=...`) and paste it into `data.txt`.

---

## Disclaimer

This bot is intended for educational purposes only. Use it at your own risk. The authors are not responsible for any consequences resulting from its use.

---

## Contributing

We welcome contributions! Please feel free to submit pull requests for improvements, additional features, or bug fixes.

---

## License

This project is licensed under the MIT License.

---

## Support and Donations

If you find this bot useful, consider supporting the project:

- **EVM**: `0x7BeE9994a631523e22A3aB83039c196bFc6BC513`
- **Solana**: `6mbFy6AojWo3J5ksa1SYHHyCWw5Bms4p9McKmaFkCsyW`

---

## Social

[![Join our Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/shadowscripters)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ShadowScripts1)

---
