# NFT-Marketplace
This is a nft-marketplace developed using nextjs , reactjs ,solidity and hardhat.
# Demo
Increase playback speed for faster viewing experience

https://user-images.githubusercontent.com/72845356/177473639-b143a828-0086-48f0-8bf5-394b358019b3.mp4

# Features
  <li>You can create (mint) new tokens, uploading their image and metadata on IPFS using Pinata.</li> 
  <li>If you've created or bought an NFT, you may also sell it by setting a price and paying a listing fee.</li>
  <li>When buying an NFT, the price will be transferred to the seller and the listing fee to the NFT Marketplace owner.</li> 
  <li>It's also possible to cancel a market item, transferring it back to the owner.</li>
   
# Installation

### Running Locally

Make sure you have Node.js and npm install.

  1. Clone or Download the repository 
    <pre>git clone https://github.com/abhinav-8/NFT-MarketPlace.git
     Copy .env.local.example to .env.local and fill it with environment variables.
     Make sure to import local Account #0 and #1 into Metamask accounts.</pre>
  2. Install metamask (it's an extension available on most of the popular browsers like firefox,safari,chrome etc. and create a network localhost 8545        with chain id 1337.
  3. Install Dependencies
      <pre>$cd NFT-Marketplace       
     $npm install</pre>
  4. Run npm run node to start a local EVM blockchain testnet.
  5. Run npm run setup to deploy NFT and Marketplace contracts and perform some initial actions to the local blockchain.
  6. Run npm run dev to start frontend application.
  7. Make sure to use Localhost 8545 as the Metamask's network.
     
  Application runs on localhost:3000.
      
## Problems encountered and solution:
<li>You may encounter errors like "nonce is too high." It may occur because you are on some other network than 8545 loclhost or you have to customize the nonce in your metamask.</li>
<li>Infura no longer supports free end point for polygon mumbai testnet.Use alchemy for the same while you can still use infura for mainnet.</li>
<li>Please help to deploy this on vercel if you can,I have tried many times but got no solution to it.</li>



   
 
