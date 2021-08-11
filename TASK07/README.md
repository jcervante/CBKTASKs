<h2>1.Screenshots or video of your application running on Godwoken.</h2>
->Deploying contract
<img src="https://github.com/jcervante/CBKTASKs/blob/main/TASK07/screenshots/img2.png">
<img src="https://github.com/jcervante/CBKTASKs/blob/main/TASK07/screenshots/img4.png">
->Make a donation 
<img src="https://github.com/jcervante/CBKTASKs/blob/main/TASK07/screenshots/img5.png">
<img src="https://github.com/jcervante/CBKTASKs/blob/main/TASK07/screenshots/img8.png">
->Withdraw balance
<img src="https://github.com/jcervante/CBKTASKs/blob/main/TASK07/screenshots/img9.png">
<img src="https://github.com/jcervante/CBKTASKs/blob/main/TASK07/screenshots/img10.png">

<h2>2.Link to the GitHub repository with your application which has been ported to Godwoken. This must be a different application than the one covered in this guide.</h2><br>
https://github.com/jcervante/AppTask09Gitcoin <br><br>
<h2>3.If you deployed any smart contracts as part of this tutorial, please provide the transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract. (Provide all in text format.)</h2>

  -Deploy transaction hash:<b>0x70164bc23855bb703f6dc313aa53e04f80464db30f887684c67c52a7d871148f </b><br><br>
  -Deployed contract address:<b> 0x2326ec6cf396F9Eb58B2e35D3c44E455a11d11b5</b><br><br>
  -ABI of the deployed smart contract:<b>
  [
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [],
      "name": "owner",
      "outputs": [
        {
          "internalType": "address payable",
          "name": "",
          "type": "address"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "getBalance",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "amount",
          "type": "uint256"
        }
      ],
      "name": "makeDonation",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "withdrawBalance",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    }
  ]</b>
