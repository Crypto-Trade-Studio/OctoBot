## Description
[Octobot](https://github.com/Crypto-Trade-Studio/OctoBot) is a powerful, fully modular open-source cryptocurrency trading robot.

See the [Octobot official website](https://github.com/Crypto-Trade-Studio/OctoBot).

This repository contains all the features of the bot (trading tools, evaluation engines, the backtesting toolkit, ...).
[Octobot's tentacles](https://github.com/Crypto-Trade-Studio/OctoBot) contains the bot's strategies and user interfaces.

To install OctoBot with its tentacles, just use the [latest release for your system](https://github.com/Crypto-Trade-Studio/OctoBot) and your OctoBot is ready ! 

Find the answers to the most common questions in [our FAQ](https://github.com/Crypto-Trade-Studio/OctoBot).

## Your Octobot

OctoBot is highly customizable using its configuration and tentacles system. 
You can build your own bot using the infinite [configuration](https://github.com/Crypto-Trade-Studio/OctoBot) possibilities such as 
**technical analysis**, **social media processing** or even **external statistics management** like google trends.

OctoBot is **AI ready**: Python being the main language for OctoBot, it's easy to integrate machine-learning libraries such as [Tensorflow](https://github.com/Crypto-Trade-Studio/OctoBot) or
any other lib and take advantage of all the available data and create a very powerful trading strategy. 

## Hardware requirements
- CPU : 1 Core / 1GHz
- RAM : 250 Mo
- Disk : 1 Go

## Installation
OctoBot's installation is **very simple**... because **very documented** ! See the [installation guides](https://www.octobot.online/guides/#installation) for more info.

#### [With executable](https://github.com/Crypto-Trade-Studio/OctoBot)
Follow the [2 steps installation guide](https://github.com/Crypto-Trade-Studio/OctoBot) 

In short:
- Use the latest release on the [release page](https://github.com/Crypto-Trade-Studio/OctoBot)

#### [With Docker](https://www.octobot.info/installation/with-docker)
Follow the [docker installation guide](https://www.octobot.online/docker_installation/) 

In short :
```
docker run -itd --name OctoBot -p 80:5001 -v $(pwd)/user:/octobot/user -v $(pwd)/tentacles:/octobot/tentacles -v $(pwd)/logs:/octobot/logs drakkarsoftware/octobot:stable
```
And then open [http://localhost](http://localhost).

With docker-compose : 
```
docker-compose up -d
```
And then open [https://octobot.localhost](https://octobot.localhost).

#### [With pip](https://octobot.click/gh-pip-install)

In short :
```
pip install OctoBot>=0.4.1
Octobot
```

#### [With python sources](https://octobot.click/gh-python-install)
Follow the [python installation guide](https://www.octobot.online/python_installation/) 

In short :
```
git clone https://github.com/Crypto-Trade-Studio/OctoBot.git
cd OctoBot
python3 -m pip install -Ur requirements.txt
python3 start.py
```

#### One click deployment
Follow the [Digital Ocean installation guide](https://github.com/Crypto-Trade-Studio/OctoBot) 

In short :

- Get 60-day free Digital Ocean hosting by registering with [OctoBot referral link](https://m.do.co/c/40c9737100b1).

- Free 24-hour demo repeatable indefinitely on Okteto simply using your Github account

## Exchanges
[![Binance]
[![Binance]
[![Binance]
[![Binance]
[![Binance]
[![Hollaex]
[![Coinbase]
[![Kucoin]
[![Bitmex]
[![Bitmax]

Octobot supports many thanks to the [ccxt library](https://github.com/ccxt/ccxt). 
To activate trading on an exchange, just configure OctoBot with your api keys as described.

## Disclaimer
Do not risk money which you are afraid to lose. USE THE SOFTWARE AT YOUR OWN RISK. THE AUTHORS 
AND ALL AFFILIATES ASSUME NO RESPONSIBILITY FOR YOUR TRADING RESULTS. 

Always start by running a trading bot in simulation mode and do not engage money
before you understand how it works and what profit/loss you should
expect.

Do not hesitate to read the source code and understand the mechanism of this bot.

