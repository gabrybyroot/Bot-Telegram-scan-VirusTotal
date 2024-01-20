# VirusTotal Scanner Bot 🦠🤖

VirusTotal Scanner Bot is a simple Telegram bot that allows users to check the threat level of a webpage using the VirusTotal API.

**Disclaimer:** I do not assume any responsibility for the use of these files by any user. I recommend using them solely for educational, professional, or testing purposes. Feel free to implement the code and make any necessary modifications with comments.

## Description
This Telegram bot integrates with the VirusTotal API to provide information about the threat level of a given webpage. It reports the number of antivirus solutions detecting the threat, the total number of antivirus solutions used for analysis, and the percentage of threat detection.

## Dependencies
- [requests](https://pypi.org/project/requests/)
- [python-telegram-bot](https://pypi.org/project/python-telegram-bot/)

## Install Dependencies
Make sure you have Python installed. You can install the required dependencies using pip:
pip install -r requirements.txt

## Add your token (Line 7)
Make sure to replace "YOUR_BOT_TOKEN" with the actual token provided by BotFather.

## Add your Api_key VirusTotal (Line 31)
Visit - [API VIRUS TOTAL](https://virustotal.readme.io/docs/api-overview)

## Running Bot:
python main.py

## Command Bot Telegram:
/scan <target> (example /scan www.google.com)
/help
/start


