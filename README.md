#ddos-attack-ovh

Powerful DDoS Attack

cd ddos-ovh

pip3 install -r requirements.txt

tmux new-session -d -s "ddos1" && tmux send-keys -t "ddos1:0" "python3 443port.py" Enter

or

python3 443port.py
