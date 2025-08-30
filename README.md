
# 🏧 ATM System in C++

This is a console-based ATM simulation built in **C++**.  
It allows users to log in with an account number and PIN, then perform basic banking operations such as withdrawing, depositing, and checking their balance.  
All client data is stored in a text file (`Clients.txt`) for persistence.

## ✨ Features
- 🔑 **Login System** with Account Number + PIN validation  
- 💸 **Quick Withdraw** (preset amounts)  
- 💵 **Normal Withdraw** (any amount in multiples of 5)  
- ➕ **Deposit** money into account  
- 📊 **Check Balance** anytime  
- 💾 **File Storage**: clients’ data is stored in `Clients.txt`  
- 🚪 **Logout** and re-login with different accounts  


## 📂 Project Structure
```

ATM-System/
│
├── ATM.cpp          # Main source code
├── Clients.txt      # Sample data file (account info)
└── README.md        # Project documentation

```


## ⚙️ How It Works
1. Program loads client information from `Clients.txt`.  
2. User logs in with **Account Number** and **PIN**.  
3. Main Menu provides options:
   - Quick Withdraw
   - Normal Withdraw
   - Deposit
   - Check Balance
   - Logout  
4. All changes (deposits/withdrawals) are saved back into `Clients.txt`.  


## 📝 Example of `Clients.txt`
Each line represents a client, fields separated by `#//#`:

```

12345#//#1234#//#John Doe#//#0123456789#//#5000
67890#//#5678#//#Jane Smith#//#0987654321#//#3000

```

**Format:**
```

AccountNumber#//#PinCode#//#Name#//#Phone#//#Balance

````


## 🚀 Getting Started

### Prerequisites
- A C++ compiler (e.g., `g++`, `clang`, or MSVC)
- Windows/Linux/Mac terminal

### Compile & Run
```bash
g++ ATM.cpp -o atm
./atm
````

---



