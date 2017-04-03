# Reddit Place Bot

The most advanced reddit place-bot currently in existence.

This is a bot based on [Reddit Place Bot](https://github.com/Zequez/placebot-argentina-target) but changed and SIGNIFICANTLY UPGRADED for the /r/eesti drawing on /r/place.


## Features
Features:
- Multi account support
- No open browser required
- Anti-multi-account-collision
- Randomized placement over specified area

## Using it for your own project

To use this bot for your project, just edit the path in `config.js` to point to your own image.

## Getting it to run

You need to have [NodeJS](https://nodejs.org) installed.  
1. Download [the repository](https://github.com/rasmussaks/reddit-placebot/archive/master.zip) and extract it into a folder.  
2. Copy the file `users.example.json` to `users.json` and add all your accounts and their passwords there.  
3. Execute the file `START.bat`

## Juhis eestlastele
1. Lase endale [NodeJS](https://nodejs.org) peale
2. Lae alla see [see fail](https://github.com/rasmussaks/reddit-placebot/archive/master.zip)
3. Paki see lahti kaustaks oma desktopil näiteks
4. Mine sinna kausta sisse ja kopeeri users.example.json ja nimeta see ümber "users.json"-iks
5. Muuda users.json faili nii, et seal oleksid sees kasutajanimi ja parool, kui sul on üks konto, tulemus peaks olema selline:  
{"kasutajanimi":"parool"}  
kui sul on mitu kasutajat (eriti kõva)  
{"kasutaja1":"parool1","kasutaja2:parool2","kasutaja3":"parool3"} jne  
MÄRKUS: Vaata, et selle faili nimi kindlalt oleks users.json ja mitte users.json.txt, sest see võib väga kergelt juhtuda. 
6. Käivita 'START.bat'
7. ???
8. Kasum

## Common issues
1. "Modash undefined" - your username or password is wrong for at least one account
