

---

# 🎯 Evilginx Session Notification Sender 🔔

**Evilginx Monitor** is a handy tool built in Go to monitor Evilginx sessions. If a valid session is captured, you can get notified via Telegram, Email, or Discord. You’re in control of how you want to be notified! 📲📧🎮

This tool can run on both **Linux** 🐧 and **Mac** 🍏, making it flexible and accessible. And the best part? It's *free* and open-source (though you use it at your own responsibility! ⚠️).

---
This has been modified to only send valid sessions, no empty logs, and will include the cookies in a randomly named zip file. 📂✅🍪

![image (4)](https://github.com/user-attachments/assets/a102ecd7-e342-44c4-bff5-3004d16c0df4)
---

## 🚀 Getting Started

Download and run the tool in interactive mode! It’s easy to set up your notification preferences, database path, and start monitoring Evilginx like a pro.

### Usage:
```bash
git clone https://github.com/clift0001/emoni.git
```
```bash
cd emoni
```
```bash
go build
```
```bash
./emoni [OPTIONS]
```

### Available Options:
- `--help`             Show this message and exit.
- `--config`           Show the current configuration.

---

## 🤖 Interactive Commands

Here's how you can get this bad boy up and running:

### Monitoring
- `start` – Start monitoring those Evilginx sessions! 🎯

### Configuration
- `config` – View the current configuration.

### Notifications

#### Telegram:
- `tele token <value>` – Set your Telegram token. 🤖
- `tele chatid <value>` – Set your Telegram chat ID. 💬
- `tele enable` – Enable Telegram notifications. ✔️
- `tele disable` – Disable Telegram notifications. ❌

#### Email:
- `mail host <value>` – Set your SMTP mail host. 🏠
- `mail port <value>` – Set your SMTP mail port. 🔌
- `mail user <value>` – Set your SMTP mail user. 📧
- `mail password <value>` – Set your SMTP mail password. 🔑
- `mail to <value>` – Set email to receive alerts. 📩
- `mail enable` – Enable email notifications. ✔️
- `mail disable` – Disable email notifications. ❌

#### Discord:
- `discord token <value>` – Set your Discord token. 🎮
- `discord chatid <value>` – Set your Discord chat ID. 💬
- `discord enable` – Enable Discord notifications. ✔️
- `discord disable` – Disable Discord notifications. ❌

### Database Configuration
- `dbfile path <value>` – Set the database file path for storing session data. 🗄️

### Exit
- `exit` – Exit interactive mode. 👋

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/clift0001/emoni.git
   ```
2. Navigate to the project folder:
   ```bash
   cd emoni
   ```
3. Build the tool:
   ```bash
   go build
   ```
4. Run the tool:
   ```bash
   ./emoni
   ```

---

## 🔧 Configuration

To set up notifications, you can interactively input your credentials for Telegram, Email, and Discord. You can enable multiple notification channels at once! 🚀

Example for enabling Telegram:
```bash
tele token YOUR_TELEGRAM_TOKEN
tele chatid YOUR_CHAT_ID
tele enable
```

---


## ⚠️ Disclaimer

This tool is for educational purposes only. How you use Evilginx and this monitoring tool is your responsibility! Use it ethically and respect privacy laws! ⚖️

---

## 🤝 Contributing

Pull requests are welcome! Feel free to fork this repository and submit your improvements. 😎

---

## 📄 License

This project is licensed under the MIT License.

---

## 🥳 Enjoy Evilginx Monitoring! 🎉

Now, go capture those sessions like a pro with Evilginx Monitor! If you like the tool, give it a ⭐ on GitHub and share it with your friends!

---

