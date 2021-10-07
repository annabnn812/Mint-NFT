on https://replit.com add packages (same like in file packages.json)


Add file Contract.json in folder src\utils    (after compiling Contaract.sol, from folder "Artifacts" file Contract.json) 


In src\App.json change:


  1. line #5 "import randomPic from './utils/RandomPic.json'"
  2. line # 11 const CONTRACT_ADDRESS = 
  3. line #72 name ABI = const connectedContract = new ethers.Contract(CONTRACT_ADDRESS, randomPic.abi, signer);
  4. line #97 name ABI = const connectedContract = new ethers.Contract(CONTRACT_ADDRESS, randomPic.abi, signer);
  5. line #99  name function Mint = console.log("Going to pop wallet now to pay gas...")  let nftTxn = await connectedContract.makeAnEpicNFT();

