# ice-tea

## FEATURES
- Auto transfer daily (100)
- Auto stake/unstake (the more you stake, the more rewards you get)
- Auto claim reward
- Auto faucet (2captcha)
- Multi-threaded, multi-account, random user agents, etc.


## Installation

1. Clone this repository

```bash
git clone https://github.com/0xDee-Coder/ice-tea.git
cd ice-tea
```
- set the ref_code & 2Captcha API key in the .env file (2Captcha will be use for Auto Faucet)
```bash
nano .env
```
2. Install dependencies
```bash
npm install
```
3. Fill Data and Proxy (Optional)

```bash
nano proxies.txt
```
5. Add Private Key
```bash
nano privateKeys.txt
```
5. Run Bot
```bash
node main
```
⚠️
- Reminder: if you don't KYC through zkPass, running the bot is useless. 
- Those wallets are only used for fauceting and then transferring to the main wallet (but doing it this way makes it easy to get sybil attacks). 
- In summary, if you have experience, play by yourself, if you want safety, besides sending to your main wallet,
- you should also send to the developer's wallet (around 5 wallets)

## Contributing

Feel free to fork this repository and submit pull requests for any improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer

This bot is for educational purposes only. Use it at your own risk. The developer is not responsible for any account-related issues or potential losses.
