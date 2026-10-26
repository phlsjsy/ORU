Rigorchain:
wallet:
https://github.com/rigorchain/rigorchain/releases/download/v0.2-mainnet/rigor-v0.2-linux-x86_64.tar.gz
chmod +x ./rigord
./rigord -server -rpcbind=127.0.0.1 -rpcallowip=127.0.0.1 -rpcuser=admin -rpcpassword=112233 -daemo
----------------------------------------
ORU---GPU挖矿、linux
chmod +x ./rigor-miner-gpu
./rigor-miner-gpu --gpu -a rgrpow01 -q --no-getwork --coinbase-addr rg1qnyqxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx -o http://127.0.0.1:8761/ -u admin -p 112233
