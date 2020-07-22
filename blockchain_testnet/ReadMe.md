Steps:

1. Download geth from geth.ethereum.org/downloads

2. To get preconfigured node 1 to mine use:

    ./geth --datadir node1 --mine --minerthreads 1 --port 30303 --rpc --ipcdisable --unlock "address"
    --allow-insecure-unlock
    
    Be sure to copy the encode
    
3. To get the preconfigured node 2 to mine use:
 
     ./geth --datadir node2 --mine --minerthreads 2 --port 30302 --bootnodes "encode here" --unlock "address"
      --allow-insecure-unlock
      
4. Use MyCrpto to communicate with node2, the transaction node:
      Set up a custom node:
      
      Click add a custom node on bottom left
      
      In popup, change ETH to custom
      
      Add node name
      
      Add network name
      
      Currency ETH
      
      add Chain ID 9999
      
      use http://127.0.0.1:8545
      
5. Then go back to other networks, change back to ETH network
      Enter mneumonic phrase
       
      inspire indoor radio slice gym among execute fever alpha network copper three
      
      choose first address 0x2326D3E915DC4249dD8bD904F02dBE391056f03D
      
      Select wallet info and copy private key
      
      Change network back to the custom network
      
      Use private key to unlock, should see an account balance
      
6. To send transaction, select send ether and tokens
       input address to send to
       
       node 1 address 0x8D585dae1b1c6818A893a87F983125844CdBE155
       
       node 2 address 0x81442fb58C24230fda38C69A63113689E078017b
       
       input amount
       
       Hit send
       