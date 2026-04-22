# 📦 Assignment 1: MessageStore Smart Contract

## 📌 Brief Description
This assignment implements a simple smart contract called **MessageStore** that allows storing and updating a message on the blockchain.  
It includes:
- A state variable to store the message  
- A constructor to initialize the message  
- Functions to update and retrieve the message  
- An event to log message updates  

---

## 🛠️ Tech Stack Used
- Solidity (0.8.x)  
- Remix IDE  
- MetaMask  
- Sepolia Testnet  

---

## 🚀 How to Run

### ▶️ Using Remix + MetaMask

1. Open Remix IDE  
2. Create/open `contract.sol` and paste the contract code  
3. Compile the contract  
4. Go to **Deploy & Run Transactions**  
5. Select **Browser Extension (MetaMask)**  
6. Connect MetaMask wallet  
7. Select **Sepolia Testnet** in MetaMask  
8. Enter initial message (e.g., "Hello Blockchain")  
9. Click **Deploy** and approve transaction in MetaMask  

---

## 🧪 Execution

- Call `getMessage()` → view stored message  
- Call `setMessage("New Message")` → update message  

## 📸 Screenshots

### 1. Smart Contract Compilation in Remix
<img width="1486" height="621" alt="image" src="https://github.com/user-attachments/assets/cbdbe7d8-698b-43d0-abc3-618da2b3c919" />


---

### 2. Contract Deployment using MetaMask (Sepolia)
<img width="1402" height="706" alt="image" src="https://github.com/user-attachments/assets/8caf1ebe-87bf-4702-a119-2548ced3ba81" />


---

### 3. Transaction Confirmation on Etherscan
<img width="1918" height="912" alt="image" src="https://github.com/user-attachments/assets/4e7c38d3-613e-45d8-a15a-555d9137dcd4" />
