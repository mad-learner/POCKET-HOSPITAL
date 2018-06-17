# POCKET-HOSPITAL
blockchain based dapp for healthcare 

# OVERVIEW

we are going to make decentralized app  named "pocket hospital" build on Ethereum platform of Blockchain for resolving the problem of distributed health care record
across healthcare providers/doctors or pathologies. 
Every such record will be stored on blockchain and each record will be mapped through a digital identity of the patient. Once the record is added on the 
blockchain, patient personal information and medical history, medical documents can be fetched from the ledger at any point of time and at any place. 

# SOL APPROCHES

In order to 
achieve this below classes/methods are used:

Entity:

1. Patient - It contains all the personal health information of the patient like Digital ID(UID) WHICH stores information like As
Blood Group and Allergies etc.

2. Medical record - It will contain all the medical records generated at hospitals, pathologies or any clinic. 

This Smart contract has a capability of storing a HexaDecimal string i.e. HASH of the Address where medical documents would be stored. 

IPFS which is a protocal used to store unalterable data, remove duplicated files across the network, and obtain address information for accessing storage nodes to search for files in the network. In our project, i am using this to store the documents like prescription, Lab reports, Xrays etc. 

This smart contract is capable of below 5 functions using the below methods written:

1. addPatient - Adds a new patient in the system and stores all of it's health information in the Blockchain.
2. getPatient - At any point of time and place, patient details can be fetched using this method.
3. addMedicalRecord - This method adds all the medical record in Blockchain and related documents like Lab reports etc in IPFS.
4. getMedicalRecord - This method can be invoked to get the details medical records stored on Blockchain.
5. getMedicalRecordDetails - This method can be invoked to get the details medical records stored on IPFS.

for permission part we tried to connect hyperledge febric for valid CA .auth. and tried to covered up with etherium firstly



# TECHNOLOGY COMPONENT

1 Ethereum blockchain /hyperledger
2 Remix
3 solidty/nodejs
4 IPFS/swam
5 TESTRPC/genache cli
6 WEBPACK/truffle/web3
