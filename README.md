Easy Install BNB Chain Node / BSC Node

UBUNTU 20.04

just copy paste the command below

```bash
git clone https://github.com/BNBChainProject/Deploy-BSC-Node-Easily.git && cd Deploy-BSC-Node-Easily && chmod +x install.sh && ./install.sh
```

if its success 

check the progress scyn
cd /opt/bsc/build/bin

then put this
```bash
./geth_linux attach http://localhost:8545 --exec eth.syncing
```
