all:
	
init_geth:
	./geth --datadir "./ethdata" init init.json

attach_geth:
	geth --rpc --rpccorsdomain "*" --datadir "./ethdata" --port 30303 --rpcapi "personal,db,eth,net,web3" --networkid 999 console
