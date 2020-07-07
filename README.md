# Logic Server

This is an encrypted copy of Logic Server for BombSquad.
This only works on Linux for now.

## Installation

Just use the following commands on any Linux Machine (preferably hosted  on cloud) and you should have a working copy in a few minutes.

You also need to edit config.py and add your account_id to admin_id variable.

```bash
sudo apt -y update
sudo apt install -y python python2.7 libsdl2-2.0.0 libpython2.7 python-pip git
git clone https://github.com/Awesome-Logic/Logic-Server.git
cd Logic-Server
```


**Important: Make sure that you properly edit the config.py as per the instructions in it.**

## Usage

The Server automatically creates a 'data' folder outside the Logic-Server folder. The contents of this folder can be used to:
- Add words to the abusive filter (filtered-words.txt)
- Add a help page (help.txt)
- Add a flyer (text that appears in the beginning of every match and smoothly transitions out after sometime) (flyer.txt)


To update the server, simply use git pull.
```bash
cd Logic-Server
git pull
```
The server will stop working if it finds a new version and is not updated.

## Feature Requests
For changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
