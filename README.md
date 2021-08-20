# ipfs-to-arweave-tutorial
pin ipfs files permanently to Arweave 



#### (If you want to pin existing IPFS files, you may skip this step)
Step 1: upload any image to ipfs using a web based tool like the one below. : 
https://anarkrypto.github.io/upload-files-to-ipfs-from-browser-panel/public/

- This will create a ipfs hash. 


### IPFS CID of a @paperbuddha 1/1 NFT that I bought 
##### Link: https://ipfs.io/ipfs/Qmc1B5NEF1vadbn16MNNJfvdf6Zet2u3R3cR1mwCxQ3rrU
##### CID: Qmc1B5NEF1vadbn16MNNJfvdf6Zet2u3R3cR1mwCxQ3rrU

Step 2:  Bash command to permapin ipfs hash to arweave: 

I'm following this tutorial: https://ipfs2arweave.com/


```
curl -X POST \
  https://ipfs2arweave.com/permapin/Qmc1B5NEF1vadbn16MNNJfvdf6Zet2u3R3cR1mwCxQ3rrU
  
```
Bash output: 
```
{"arweaveId":"HYvcCQvtGsF2j1qD8f2KtkiyYONZQtZeajhTjlmLSQ4","ipfsHash":"Qmc1B5NEF1vadbn16MNNJfvdf6Zet2u3R3cR1mwCxQ3rrU","statusCode":200}%    
```

---


### Step 3- veiw Files on Arweave by using the arweave id that came out of the bash command
arweave.net/HYvcCQvtGsF2j1qD8f2KtkiyYONZQtZeajhTjlmLSQ4


---
Note: Arweave is subsidising the storage at the moment and they contribute to the endowment. Eventually the users will have to pay for their own endowment contributions, but the data already stored (of course) will be permanent. 



