# Codefundo-2019

## **Background**:

During every election, each potential voter has to present himself for verification before Booth Level Officer with his valid id proof and other official documents so that he can get registered for that election. And there is always a possibility for electoral fraud like Booth capturing, Vote Rigging, EVM hacking etc. Our Idea tries to tackle these problems. 

## **Our Idea**:
We came up with an idea of making a Python-based Django project which will simulate a concept of blockchain-based e-voting system. We can verify the voter using face recognition system embedded inside the application itself. The blockchain part of the project has two subparts: **BLOCK** and **CHAIN**.

### **BLOCK**:
In this section, a voter can cast his vote for a particular candidate by entering his ID and a private key will be required for signing the ballot. If the submitted ballot is found to be valid then it will be sealed. Note that one block contains only the aforementioned ballot.

### **CHAIN**:
All the transactions with valid data will be generated in this section. The data will be sealed into blocks and after that you can explore the blocks, verify the transactions.


## **Problems Solved**:
•	**Privacy**: Blockchain will ensure data security. <br />
<br />
•	**Tampering**: It would be nearly impossible for someone to tamper any block in the blockchain due to decentralised ledger. <br />
<br />
•	**Feasibility**: E-voting will be more convenient compared to the manual way of voting.


## **Tools Used**:

•	Microsoft Azure Blockchain will be used for deploying Blockchain. <br />
<br />
•	Django will be used for Web Application. <br />
<br />
•	Python as the primary language. <br />
<br />
•	CSS and JS for front-end development.
