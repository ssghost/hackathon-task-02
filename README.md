# hackathon-task-02

I have followed all the descriptions on the page of Task 02 and implemented all the required progresses. Here are the steps:

 - Created a template of Rust code base and write a lib.rs file to implement 3 functions: init, receive, view. Built a module "my-project.wasm.v1" and passed the test written for it. All these steps using "Cargo Concordium", the proofs of completion of those steps can be seen in "Screenshot_Cargo_init.png", "Screenshot_Cargo_build.png", "Screenshot_Cargo_test.png".

 - Finished some preparations for "Concordium-client", including import account keys from wallet, and use online faucet to get some CCDs on Testnet. Proofs are "Screenshot_Client_import.png", "Screenshot_Node_install.png", "Screenshot_Faucet.png".

 - Successfully deployed the module "my-project.wasm.v1" on CCD Testnet, initialized the contract after deployment, and furthermore, performed some basic interactions with this contract on-chain with "Concordium-client". All these interactions are recorded in the screenshots mentioned below: "Screenshot_Contract_deploy.png", "Screenshot_Contract_init.png", "Screenshot_Contract_update.png", "Screenshot_Contract_invoke.png" and a text file for the record of contract inspection "Contract_inspect.txt".

 - Finally we can see in the screenshot of invoke operation, the parameter "value" stored in this contract had been successfully changed to "42".

 Deploy TxHash: bf643b72f8b24dd8d34e131e687369e7786526cc11a1546504a53cd49e9e21cd

 Init TxHash: f4c53a0c0c43aa649db45ef8c829aa1f61b0e2c597f11ba644c41a1cbe28b963
 
 Update TxHash: 3b9cd38296763a78671a3b6626fc97baea051dea3035e283348f4e714a10b2da

 Update Params please see file "params.json"
