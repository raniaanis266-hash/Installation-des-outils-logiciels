# Installation-des-outils-logiciels
A.1 Installation de Mininet et Open vSwitch
sudo apt install mininet openvswitch-switch -y
mn --version
ovs-vsctl --version
A.2 Installation du contrôleur Ryu
sudo apt install python3-pip -y
pip3 install ryu
ryu-manager --version
A.3 Installation des bibliothèques Machine Learning
sudo apt install python3-pip -y
pip3 install flask scikit-learn pandas joblib requests
Vérification de l'installation dans l'environnement Python :
python3
import flask
import sklearn
import pandas
import joblib
Installation des outils de test réseau (iperf, hping3, nmap)
sudo apt install iperf -y
iperf --version
hping3 --version
nmap --version
