# Sc-Google-Colab-Proo- Mining Eth 


silahkan tinggal coopy paste aja free suspend 2-3 hours
Google Collab ;
https://colab.research.google.com/drive/1CdJc3ksHzWwY_5lSqS4D13IFOXLwdbuh?hl=id

!nvidia-smi

sudo add-apt-repository ppa:ethereum/ethereum

sudo cat /etc/apt/sources.list

sudo apt update

sudo apt install ethereum

wget https://github.com/ethereum-mining/ethminer/releases/download/v0.18.0/ethminer-0.18.0-cuda-9-linux-x86_64.tar.gz

%ls

tar -zxvf ethminer-0.18.0-cuda-9-linux-x86_64.tar.gz

%cd bin/

./ethminer -G -P stratum1+tcp://WALLET_ADRESS@eth-asia1.nanopool.org:9999
