📷 Preview
https://medal.tv/games/gta-v/clips/kZ8KB0XuY4f2gNsgN?invite=cr-MSxnUm4sODA2OTMwMzM&v=92

🚗 How to Install ESX Garage System on Your Server

This guide will show you how to add the ESX Garage System to your FiveM server.

Download the Resource

Download the ZIP from GitHub (or your release link).
Example:

[https://github.com/YourUsername/esx_garage/archive/refs/heads/main.zip](https://github.com/0SammY00/-ESX-Garage-System)


Extract the Files

Unzip the downloaded file.

You should get a folder named esx_garage containing .lua files, fxmanifest.lua, config.lua, SQL, and LICENSE.

Upload to Server

Place the esx_garage folder inside your server resources folder:

resources/[esx]/esx_garage


Add to server.cfg

Open server.cfg and add:

ensure esx_garage


Database Setup

If your resource includes an SQL file (esx_garage.sql):

Open your database (phpMyAdmin, Adminer, or MySQL client).

Import the SQL file.

Make sure your database connection is working (oxmysql or mysql-async).

Configure the Resource

Open config.lua and adjust garage locations, markers, or database table names as needed.

Save changes.

Restart Server

Start or restart your server.

Test in-game by approaching a garage marker to store and retrieve vehicles.

Keep the LICENSE

Make sure the LICENSE file stays in the resource folder to comply with your chosen license (MIT or GPL).
