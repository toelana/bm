# BlockMesh Network Autoreferral Bot
Automatic referral script for BlockMesh Network Account using proxies.
### Tools and components required
1. BlockMesh Network Account | Register: [https://app.blockmesh.xyz/register](https://app.blockmesh.xyz/register?invite_code=officialblockmesh)
2. Proxies Static Residental | [FREE 10 PREMIUM PROXIES](https://www.webshare.io/?referral_code=p7k7whpdu2jg) | [Free 100 Premium Proxies](https://proxyscrape.com/?ref=odk1mmj) | Good Premium Proxies (paid): [922proxy](https://www.922proxy.com/register?inviter_code=d03d4fed), [proxy-cheap](https://app.proxy-cheap.com/r/JysUiH), [infatica](https://dashboard.infatica.io/aff.php?aff=544)
3. VPS or RDP (OPTIONAL)
4. Python3 Latest Version
# Installation
- Install Python For Windows: [Python](https://www.python.org/ftp/python/3.13.0/python-3.13.0-amd64.exe)
- For Unix:
```bash
apt install python3 python3-pip -y
```
- Install requirements, Windows:
```bash
pip install -r requirements.txt
```
- Unix:
```bash
pip3 install -r requirements.txt
```
### Run the Bot
- Replace the proxies example in ```proxies.txt``` to your own proxies with format:
```bash
http://host:port
http://user:pass@host:port
```
>only http proxies support for now, if you want to run without proxies, just remove proxies.txt content or delete proxies.txt
#### Run command:
- Windows:
```bash
python main.py
```
- Unix
```bash
python3 main.py
```
- Insert your full referral URL, example: ``https://app.blockmesh.xyz/register?invite_code=XXXXXXXXXX``
- Enter how many referrals you want
- Result account generated will be saved to ``accounts.txt``
# Notes
- Run this bot, and it will update your referrer code to my invite code if you don't have one.
- You can just run this bot at your own risk, I'm not responsible for any loss or damage caused by this bot. This bot is for educational purposes only.
