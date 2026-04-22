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
![Compilation](screenshots/01.png)

---

### 2. Contract Deployment using MetaMask (Sepolia)
![Deployment](screenshots/02.png)

---

### 3. Transaction Confirmation on Etherscan
![Etherscan](screenshots/03.png)