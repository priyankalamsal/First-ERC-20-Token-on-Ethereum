# MyToken (MTK)

A simple ERC-20 token built for learning purposes as part of my blockchain development assignment.  
This token is fully compatible with the ERC-20 specification and includes all required functions and events.

---

## 📌 Token Details
| Property       | Value          |
|----------------|----------------|
| **Name**       | MyToken        |
| **Symbol**     | MTK            |
| **Decimals**   | 18             |
| **Total Supply** | 1,000,000 MTK (example during deployment) |

---

## 📘 What is an ERC-20 Token?
ERC-20 is the **Ethereum token standard** that defines how tokens behave.  
It ensures:

- All wallets can recognize the token  
- Exchanges can list it  
- Smart contracts can interact with it  

Functions like `transfer`, `approve`, and `transferFrom` are required.

---

## ✅ Implemented Features
- Full ERC-20 compatibility  
- Token transfer (`transfer`)  
- Allowance + approvals (`approve`)  
- Delegated transfers (`transferFrom`)  
- Balance tracking  
- Emission of required events (`Transfer`, `Approval`)  
- Input validation (zero address, insufficient balance, insufficient allowance)

---

## 🚀 Deployment Instructions (Remix IDE)

1. Open **https://remix.ethereum.org**
2. Create folder `contracts/` → add file `MyToken.sol`
3. Paste the contract code
4. Go to **Solidity Compiler** → choose version `0.8.x`
5. Compile the contract
6. Go to **Deploy & Run**
   - Environment: **JavaScript VM**
   - Constructor value:  
     **1000000 × 10^18 = 1000000000000000000000000**
7. Click **Deploy**

---

## 🧪 Usage Examples

### 1. Check Balance
