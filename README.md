##TRANS.C

# 🏦 Banking System in C

A secure **file-based banking system** implemented in C.  
It allows account creation, deposits, withdrawals, searching, listing by balance, exporting active accounts, and account summary reporting — all with **PIN-based authentication** and a **Master PIN** for admin access.

---

## 🚀 Features
- Master PIN authentication for system access  
- Create, update, and delete accounts (1–2000)  
- Deposit and withdrawal transactions with tracking  
- PIN verification for sensitive operations  
- Simple PIN encryption & decryption (XOR-based)  
- Search accounts by name (partial & case-insensitive)  
- List accounts filtered by balance thresholds (above/below)  
- Export active accounts to `active_accounts.txt`  
- Generate account summaries (total/active accounts, financial stats)  
- Cleanup accounts without PINs  

---

## 🛠️ Requirements
- **C Compiler** (GCC recommended)  
- Standard C libraries (`stdio.h`, `stdlib.h`, `string.h`)  

---

## 📂 Project Structure

