
[Cheat Engine](http://cheatengine.org/) table files for Sub Rosa Alpha 33.

Work in progress.

# Server notes

Only meant to be working with subrosadedicated.exe from Alpha 33a, not Alpha 33c.

SRU mod includes following custom admin commands:

``` 
players are typed in as a case-sensitive substring, like "Tony" for "Tony Montana"
teams are typed in as numbers (0,1,2. 7 for observers)

/flimpo                   - toggle between round mode and tdm
/ready                    - force ready up in tdm mode
/rg                       - short for /resetgame
/tc num                   - set the amount of traffic cars (no argument to show current value)
/fpos                     - display your current coordinates

/mv player, team          - move player to another team
/op player                - make player an admin
/rn player,new_name       - rename player
/pre player,tag           - prepend to player's name
/kill player              - kill player in the game
/spawnhelp player         - spawn right next to the player
/mute player              - make player unable to type in observer chat

/skip                     - set timer to 00:01
/locktime                 - lock the time at the current state

/resetcash                - reset everyone's cash, stocks, inventory and company stock prices
/shift                    - rotate the teams
/setcash player,cash      - set player's cash (also sets stocks to 0)
```

GeoIP requires "luaclient-i386.dll" and "geoip" in the game folder. (see my PUBG-mod repository)

# Client notes

# IDs

```

Teams

0 - Goldmen
1 - Monsota
2 - OXS International
6 - Bots
7 - Spectators

Items

00  0 Auto 5
01  1 AK-47
02  2 AK-47 Magazine
03  3 M-16
04  4 M-16 Magazine
05  5 Magnum
06  6 .45 Bullets
07  7 MP5
08  8 MP5 Magazine
09  9 Uzi
0a 10 Uzi Magazine
0b 11 9mm
0c 12 9mm Magazine
0d 13 Grenade
0e 14 Bandage
0f 15 Briefcase
10 16 Open Briefcase
11 17 Cash
12 18 Cash
13 19 Black disk
14 20 Green disk
15 21 Blue disk
16 22 White disk
17 23 Gold disk
18 24 Red disk
19 25 Cell Phone
1a 26 Key
1b 27 Door
1c 28 Newspaper
1d 29 Burger
1e 30 Desk
1f 31 Lamp
20 32 Pay Phone
21 33 Memo
22 34 Soccer Ball
23 35 Rope


Vehicles

00  0 Town Car
01  1 Town Car 2
02  2 Metro
03  3 Limo
04  4 Turbo
05  5 Turbo S
06  6 Beamer
07  7 Van
08  8 Minivan
09  9 Truck
0a 10 Trailer
0b 11 Heli
0c 12 Train
0d 13 (Train)
0e 14 Hatchback
0f 15 Test

```

# Contributors

Tony Montana

Gray

InvaderMoo