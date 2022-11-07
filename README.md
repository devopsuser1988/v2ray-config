## On foreign server (server 1):

* $ mkdir v2ray
* $ cd v2ray
* $ sudo curl -s https://raw.githubusercontent.com/devopsuser1988/v2ray-config/main/install-upstream.sh | bash -s 2084

After the script will be finished, It types a command like following, please run that on your local server :

  sudo curl -s https://raw.githubusercontent.com/devopsuser1988/v2ray-config/main/install-bridge.sh | bash -s x.x.x.x 2084 xxxxxxxx-xxx-xxx-xxxx-xxxxxxxxxxx

## On local server (server 2):

* $ sudo curl -s https://raw.githubusercontent.com/devopsuser1988/v2ray-config/main/install-bridge.sh | bash -s x.x.x.x 2084 xxxxxxxx-xxx-xxx-xxxx-xxxxxxxxxxx


