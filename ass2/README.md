# 📦 Assignment 2: Deploy Smart Contract on Polygon Testnet

## 📌 Brief Description
In this assignment, the previously developed **MessageStore smart contract** is deployed on the **Polygon Amoy Testnet** instead of Ethereum.  
This demonstrates improved scalability and lower transaction cost using the Polygon network.

---

## 🛠️ Tech Stack Used
- Solidity (0.8.x)  
- Remix IDE  
- MetaMask  
- Polygon Amoy Testnet  

---

## 🚀 How to Run

### ▶️ Step 1: Setup Polygon Network in MetaMask
- Open MetaMask  
- Go to Settings → Networks → Add Network  
- Enter:
  - Network Name: Polygon Amoy  
  - RPC URL: https://rpc-amoy.polygon.technology/  
  - Chain ID: 80002  
  - Currency Symbol: POL  

---

### ▶️ Step 2: Get Test Tokens
- Visit: https://faucet.polygon.technology/  
- Select Amoy network  
- Enter wallet address and request POL  

---

### ▶️ Step 3: Deploy Contract using Remix
1. Open Remix IDE  
2. Open `contract.sol`  
3. Compile the contract  
4. Go to **Deploy & Run Transactions**  
5. Select **Browser Extension (MetaMask)**  
6. Connect MetaMask and ensure network is **Polygon Amoy**  
7. Enter constructor value (e.g., "Hello Polygon")  
8. Click **Deploy** and confirm in MetaMask  

---

## 🧪 Execution
- Call `getMessage()` → view stored message  
- Call `setMessage("New Message")` → update message  

---
## 📸 Screenshots

### 1. MetaMask Network Setup (Polygon Amoy)
<img width="468" height="858" alt="image" src="https://github.com/user-attachments/assets/dc9d99f4-23ea-4ee6-a222-7a8ff541cea0" />


---

### 2. Smart Contract Deployment in Remix
![Remix Deployment](screenshots/02.png)

---

### 3. Transaction Confirmation on PolygonScan
<img width="1917" height="911" alt="image" src="https://github.com/user-attachments/assets/c3be04fe-ff80-49b1-9cb6-e8daf16fb4c5" />
