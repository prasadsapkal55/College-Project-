# ShareHub - File Sharing Application

![ShareHub Logo](media/image1.png)

## 📌 Overview
ShareHub is an intuitive file transfer application designed to streamline the process of exchanging data between users over a network. Built with Python and Tkinter, it offers a user-friendly interface with features like light/dark mode, secure file transfers, and local database storage for file history.

## ✨ Key Features
- **User-Friendly Interface**: Simple and intuitive GUI for seamless file transfers.
- **Light/Dark Mode**: Toggle between themes for better visibility and comfort.
- **Secure Transfers**: Uses socket programming for reliable file sharing.
- **Database Integration**: Stores sent and received file details in SQLite databases.
- **Cross-Platform**: Compatible with Windows, macOS, and Linux.

## 🛠️ Technologies Used
- **Frontend**: Tkinter (Python)
- **Backend**: Python (Socket Programming, SQLite)
- **Database**: SQLite (`sender.db` and `receiver.db`)

## 📦 Installation
1. **Prerequisites**:
   - Python 3.x installed on your system.
   - Tkinter (usually included with Python).

2. **Steps**:
   ```bash
   git clone https://github.com/prasadsapkal55/College-Project-.git
   cd ShareHub
   python main.py
   ```

## 🖥️ Screenshots
| Light Mode | Dark Mode |
|------------|-----------|
| ![Light Mode](media/image5.png) | ![Dark Mode](media/image6.png) |

| Send File | Receive File |
|-----------|-------------|
| ![Send](media/image7.png) | ![Receive](media/image8.png) |

## 📂 File Structure
```
ShareHub/
├── main.py                # Main application script
├── sender.db              # Database for sent files
├── receiver.db            # Database for received files
├── Image/                 # Contains GUI assets
│   ├── icon.png           # Application icon
│   ├── send.png           # Send button icon
│   ├── receive.png        # Receive button icon
│   └── ...                # Other images
└── README.md              # Project documentation
```

## 🧪 Testing
- **Unit Testing**: Verified core functionalities like file sending/receiving and database operations.
- **Integration Testing**: Ensured seamless interaction between GUI, networking, and database modules.
- **Usability Testing**: Confirmed intuitive user experience across light/dark modes.


## 🙏 Acknowledgments
- **Institution**: Karmaveer Bhaurao Patil College, Vashi
- **References**: Python Documentation, SQLite Browser, and online tutorials.

---

🌟 **Happy Sharing with ShareHub!** 🌟  