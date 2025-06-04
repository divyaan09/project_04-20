# 🧪 Simple Malware Scanner in Java (Without YARA)

A beginner-friendly Java project that scans files for known malware signatures using plain text pattern matching.

## 🚀 Features

- Scans any text file for known malware strings.
- No external libraries or YARA required.
- Fully written in plain Java.

## 📁 Project Structure

```
simple-malware-scanner/
├── src/
│   └── SimpleMalwareScanner.java
├── signatures.txt
├── sample_file.txt
```

## 🛠️ How to Use

1. **Edit `signatures.txt`**  
   Add your known malicious keywords (one per line).

2. **Place file to scan**  
   Edit or replace `sample_file.txt` with the file you want to scan.

3. **Compile the Program**  
   ```bash
   javac src/SimpleMalwareScanner.java
   ```

4. **Run the Scanner**  
   ```bash
   java -cp src SimpleMalwareScanner
   ```

## 🧠 Example Output

```
⚠️ Malware signature found: malicious_code
```

## 📌 Notes

- This scanner uses simple keyword matching.
- It does **not** detect encrypted or polymorphic malware.
- Meant for educational/demonstration use only.

## 📄 License

This project is released under the MIT License.
# project_04-30
