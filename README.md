# Unich BOT
Unich AutoBot

- Register Here : [Unich](https://unich.com/en/airdrop/sign-up?ref=L3VBNL)
- Use Code : L3VBNL

## Features

  - Auto Get Account Information
  - Proxy Support
  - Auto Claim Tasks
  - Auto Start Mining
  - Multi Accounts

## Requirements

- Make sure you have Python3.9 or higher installed and pip.
- Proxy, use private proxy, don't use free one

## Proxy Setup
### Recommended Proxy Providers
- Residential Proxies
  * [Nstp](https://app.nstproxy.com/register?i=42Um5k)
- Proxyscrape
  * [ProxyScrape](https://proxyscrape.com/)

## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/kelliark/Unich-AutoBOT
   ```
   ```bash
   cd Unich-AutoBOT
   ```

2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```

## Configuration


- **How to get Beare Token:** 
  * Go To Network Tab and Control + R to Reload and then go to the tab in Network Tab called `my-info` and scroll down and then copy the Bearer Token, the thing that starting with eyj....

- **tokens.txt:** You will find the file `tokens.txt` inside the project directory. Make sure `tokens.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    eyjxxxxx1
    eyjxxxxx2
  ```
- **proxy.txt:** You will find the file `proxy.txt` inside the project directory. Make sure `prxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    http:user:pass@ip:port
    http:user:pass@host:port
    protocol://username:password@ip(host):port
  ```

## Run

```bash
python bot.py
```

## Notes
- You can run this bot at your own risk, I'm not responsible for any loss or damage caused by this bot.
- This bot is for educational purposes only.
