#ddos-attack-ovh

Powerful DDoS Attack

sudo apt install python3-pip

sudo apt install tmux

cd ddos-ovh

pip3 install -r requirements.txt

tmux new-session -d -s "ddos1" && tmux send-keys -t "ddos1:0" "python3 443port.py" Enter

or

python3 443port.py
