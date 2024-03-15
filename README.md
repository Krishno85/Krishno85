pkg update -y
pkg upgrade -y
pkg install git -y
pkg install python -y
pkg install figlet -y
git clone https://github.com/STLP-TEAM/TERMUX-SETUP
cd TERMUX-SETUP
python main.py
