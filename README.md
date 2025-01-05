# Instructions of Installation & Running Game Server
- To Make a Cloud Server, <a href="">click here</a> OR skip to next step if you are already ready with ubuntu OR if you just want to run in local Ubuntu
- For running in Local Ubuntu, <a href="https://github.com/EggFiry1027/hello-world/edit/main/README.md#installation">click here</a>
## Installation
- Copy The following command text as is and paste it in ubuntu terminal & run it
```
sudo add-apt-repository ppa:deadsnakes/ppa -y
sudo apt update && sudo apt upgrade -y
sudo apt install software-properties-common python3-pip python3.12-dev python3.12-venv python3-tinydb git -y
git clone https://github.com/HeyFang/bombsquad-modded-server-scripts.git
cd bombsquad-modded-server-scripts
chmod +x ballisticakit_server dist/ballisticakit_headless
```
- This Should have Installed all the necessary Packages

