# Hospital Administration Management System (HAMS)

A C++ hospital IT management system designed for academic submission, portfolio showcase, and real-world deployment.  
It includes role-based access control, audit logging, and a menu-driven interface with log filtering.

---

## ✨ Features
- 🔑 *Role-based access control* (Administrator, Doctor, Nurse)
- 🔒 *Secure password hashing* (SHA-256 via OpenSSL)
- 📝 *Audit logging* (records both successful and failed actions)
- 📊 *Log filtering* (view failed attempts or filter by role)
- 💾 *File persistence* (users and patients stored in text files)
- 🖥️ *Menu-driven interface* (interactive console system)

---

## 📂 Project Structure
HAMS/
├── core/            # Hospital system logic
├── security/        # Password hashing
├── notifications/   # Console notifications
├── audit/           # Audit logging
├── data/            # Persistent storage (users, patients, logs)
├── CMakeLists.txt   # Build configuration
├── main.cpp         # Entry point
├── README.md        # Project documentation
├── LICENSE          # MIT License
`
---

## 🛠️ Build Instructions

### Prerequisites
- C++17 compiler (g++)
- CMake (>= 3.10)
- OpenSSL development libraries

### Build & Run
```bash
mkdir build && cd build
cmake ..
make
./HAMS
📸Screenshots (Console Output)

[NOTIFICATION]: Hospital Administration Management System started!

--- HAMS Menu (Administrator) ---
1. Add User
2. Authenticate User
3. Add Patient
4. List Patients
5. Exit
6. View Audit Log
7. Filter Audit Log
Choose an option: 3
Enter patient name: John Doe
Enter age: 45
Enter diagnosis: Flu
Patient John Doe added.

🪪This project is licensed under the MIT License — see the [Looks like the result wasn't safe to show. Let's switch things up and try something else!] file for details.

---

👨‍💻 Author
Developed by RICHARDJUMA 
Third-year Bachelor of Information Technology student, University of Eldoret.
`

---

## 🚀 Next Steps
1. Save this as README.md in your project root.  
2. Stage and commit it:
   ```bash
   git add README.md
   git commit -m "Added professional README"
   git push



