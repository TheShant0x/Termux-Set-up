# Termux Setup Commands

```bash
termux-change-repo
# → Group rotate
# → Official mirrors choose (India / Global / Default)
termux-setup-storage
pkg update -y
pkg upgrade -y
pkg install python -y
pkg install git -y
pkg install php -y
pkg install curl -y
pkg install wget -y
pip install requests
pip install mechanize
pip install bs4


### Installation or Set up Check
python --version
pip --version
git --version
pkg list-installed


### Check Storage Permission
ls ~/storage


### Cleanup: Unnecessary cache remove & Space safe (Optional)
pkg autoclean
pkg clean
