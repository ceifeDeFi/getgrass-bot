@getgrass-Bot

This is a bot specifically designed for the second season of GetGrass airdrops.

Features

✅ Supports multiple UIDs

✅ Allows custom proxies

Installation Steps

Clone this repository to your local environment:

git clone https://github.com/ziqing888/getgrass-bot.git

Enter the project directory:

cd getgrass-bot

Install required dependencies:

npm install

Usage Instructions

Get the user ID:

1. Log in to the GetGrass website: https://app.getgrass.io/register/?referralCode=x2WrNmdmnoG-YuX


2. Open your browser's developer tools (usually by pressing F12 or by right-clicking and selecting "Inspect").


3. Switch to the "Console" tab.


4. Enter the following command and press Enter:



localStorage.getItem('userId');

5. Copy the returned value – this is your user ID.



Create a user ID file:

In the project directory, create a file named uid.txt and write one user ID per line, for example:

123123213
12313123

Add proxy information:

Create a file named proxy.txt and add your proxy URLs line by line in the following format:

http://username:password@hostname:port
socks5://username:password@hostname:port

Start the bot:

Run GetGrass-Bot with the following command in the terminal:

npm start

Recommended Proxy: ▫️ Affordable Proxies:
https://iproyal.com/?r=645571

