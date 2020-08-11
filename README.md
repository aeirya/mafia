# mafia
:dollar: Web Server Application For Mafia Game Playing On Local Network

## Usage
After cloning into mafia using command bellow:
```
$git clone https://github.com/sadrasabouri/mafia
```
You should do these tiny steps:
1. Instaling requiremets:
First check if you have `pip3` installed in your system:
```
$pip3 --version
pip 20.0.2 from /usr/lib/python3/dist-packages/pip (python 3.8)
```
if you already have installed `pip3` youu should see something like above, otherwise run the command bellow to install it:
```
$sudo apt install python3-pip
```
Otherwise/Then install <b>mafia</b> requirements by
```
$pip3 install -r requirements.txt
```
Now everything is ready, lets play:
run the command `$python3 mafia.py number_of_players[int]`, for example imagine you want to play mafia with 5 players.
```
$python3 mafia.py 5
```
There you go, now each player can open a browser and type `serverhost:port_name`.

In defualt mode your desired address should be `server_ip:5000`.

Each player should see a page like this in his/her browser:
<img src="https://raw.githubusercontent.com/sadrasabouri/mafia/master/doc/Pictures/mobile_browser.png">
And the GOD can track player's role by checking CLI:
<img src="https://raw.githubusercontent.com/sadrasabouri/mafia/master/doc/Pictures/CLI.png">

### Roles
| Role            | image(s)                                                                                                                                |
| :-------------: |:----------------------------------------------------------------------------------------------------------------------------:           |
|      Don        | <img width="100" height="100" src="https://raw.githubusercontent.com/sadrasabouri/mafia/master/static/images/roles/Don_1.png">          |
|     Mafia       | <img width="100" height="100" src="https://raw.githubusercontent.com/sadrasabouri/mafia/master/static/images/roles/Mafia_1.png"><img width="100" height="100" src="https://raw.githubusercontent.com/sadrasabouri/mafia/master/static/images/roles/Mafia_2.png">                                                          |
|      Rebel      | <img width="100" height="100" src="https://raw.githubusercontent.com/sadrasabouri/mafia/master/static/images/roles/Rebel_1.png">        |
|     Doctor      | <img width="100" height="100" src="https://raw.githubusercontent.com/sadrasabouri/mafia/master/static/images/roles/Doctor_1.png"><img width="100" height="100" src="https://raw.githubusercontent.com/sadrasabouri/mafia/master/static/images/roles/Doctor_2.png">                                            |
|    Detective    | <img width="100" height="100" src="https://raw.githubusercontent.com/sadrasabouri/mafia/master/static/images/roles/Detective_1.png">    |
|   Anti-attack   | <img width="100" height="100" src="https://raw.githubusercontent.com/sadrasabouri/mafia/master/static/images/roles/Anti-attack_1.png">  |
|     Resident    | <img width="100" height="100" src="https://raw.githubusercontent.com/sadrasabouri/mafia/master/static/images/roles/Resident_1.png"><img width="100" height="100" src="https://raw.githubusercontent.com/sadrasabouri/mafia/master/static/images/roles/Resident_2.png"><img width="100" height="100" src="https://raw.githubusercontent.com/sadrasabouri/mafia/master/static/images/roles/Resident_3.png"><img width="100" height="100" src="https://raw.githubusercontent.com/sadrasabouri/mafia/master/static/images/roles/Resident_4.png">                                                                                                                 |

## References
Icons made by <a href="https://www.flaticon.com/authors/vectors-market" title="Vectors Market">Vectors Market</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>