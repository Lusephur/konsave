# Consave (Save Plasma Customization)
A CLI program that will let you save and apply your KDE Plasma customizations with just one command!
![SS_2021-02-27_22-44-17](https://user-images.githubusercontent.com/39525869/109394503-5fb3e580-794d-11eb-8637-70e87e2b0c26.png)

---
## Dependencies
There are no dependencies! Just make sure your python version is above `3.8`.

## Installation
- Clone This repo  
`git clone https://github.com/Prayag2/consave ~/Downloads/consave`
- Make it executable  
`cd ~/Downloads/consave`
`sudo chmod +x ./install.sh`
- Install  
`./install.sh`

## Usage
### Get Help
`consave -h`
### Save current configuration as a profile
`consave -s <profile name>`
### List all profiles
`consave -l`
### Remove a profile
`consave -r <profile id>`
### Apply a profile
`consave -a <profile id>`  
You may need to log out and log in to see all the changes.  
## Contribution
You can contribute by reporting issues or fixing bugs!

## License
This project uses GNU General Public License 3.0