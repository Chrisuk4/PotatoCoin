Potatocoin
================================

Website Will be coming up in the future

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2014 Litecoin Developers
Copyright (c) 2020-2022 Potatocoin Developers

What is Potatocoin?
----------------

Potatocoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.

For more information, Contact me on Discord at Potato_Squid #8338 or send me a Email at christiankallio.ck10@gmail.com

How to Start Mining PTC
----------------

To start Mining PotatoCoin you need a Ubuntu linux Virtual Machine or a full system with it

After putting up your Virtual Machine you need to download the PotatoCoin Executable

Run the executable once and after it starts up the first time go to your file explorer and open up the homen directory.
Press Ctrl+H to show hidden files and open up .potatocoin folder.

Make a new file called potatocoin.conf and edit it, To add a ip of a node you need to write "addnode=" + Node Ip without spaces.

If you want to add multiple ip:s you can repeat the "addnode=" in a new row.

After all node ip:s have been added you can start up the app.

The app has a simple wallet GUI and a Simple inbuilt Cpu Miner with some other small extras.

To start Mining you need to open up the help tab and go into console.

When in the console you can write "setgenerate true" to start mining on all available cores, If you want to Limit the amount
of cores the miner can use you can write "setgenerate true 1" to only use 1 core.

If you want to see your Hashrate and other information you can write "getmininginfo".

How to use Testnet
----------------

To launch the wallet miner in testnet mode you need to open a terminal in the folder where potatocoin-qt exists and write "potatocoin-qt -testnet".

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
