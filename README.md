
## 📇 Contact Record Manager

A simple Java console-based application that allows users to input and store contact information—Name, Phone Number, and Email—into a local file. Designed for quick data entry and retrieval, this tool is ideal for basic visitor or contact logging.

---

### 🚀 Features
- ✅ Interactive CLI for entering contact details
- ✅ Stores data in a comma-separated format
- ✅ Uses semicolon (`;`) to separate individual records
- ✅ Appends new entries to `visitors.txt`
- ✅ Reads and displays all saved records after input

---

### 🛠️ Technologies Used
- Java SE
- File I/O (`File`, `PrintWriter`, `BufferedReader`)
- `StringJoiner` for clean formatting
- Modular design with `FileManager` utility class

---

### 📂 File Structure
```
ContactRecordManager/
├── Main.java          # Handles user input and program flow
└── FileManager.java   # Manages file creation, writing, and reading
```
