# Ordina-Arcade-Manual
A short manual for using the Ordina Arcade hosted here: https://chocolatepinecone.github.io/Ordina-Arcade-Manual/

## How to connect to the internal retropie wirelessly
The Ordina network blocks connections from one device to another, so it's necessary to create our own managed network in order to set up a working connection.
I use my mobile phone to create a wifi hotspot with which I connect the retropie and my laptop.
The steps to create a connection this way are the following:
1. Create a wifi hotspot with your phone
2. Connect the retropie and your laptop to the hotspot
3. Ping the retropie from your laptop to assure there is a connection: ```ping retropie```
4. Use WinSCP or another ssh/sftp program to make a connection using the following settings:
```
ip-address: retropie
port: 22
username: pi
password: raspberry
```
5. Now you can adjust files or transfer roms if needed
