# 💊 Pharmaceutical Interaction Engine

## 🚀 Overview

The **Pharmaceutical Interaction Engine** is a smart system designed to detect potentially dangerous drug interactions from encrypted or corrupted prescriptions. It combines cryptography, intelligent text correction, and graph-based analysis to ensure patient safety.

---

## 🎯 Problem Statement

Medical prescriptions may be:

* 🔐 Encrypted (for privacy/security)
* ⚠️ Corrupted or misspelled

This can lead to **undetected drug interactions**, causing serious health risks.

---

## 💡 Solution

Our system performs the following steps:

1. 🔓 **Decrypts prescriptions** using Caesar Cipher
2. 🧠 **Corrects drug names** using fuzzy matching
3. ⚠️ **Detects drug interactions** from a predefined database
4. 🚨 **Identifies high-risk combinations**
5. 🌐 **Visualizes interactions** using a graph-based model

---

## ⚙️ Features

* 🔐 Cipher-based prescription decoding
* 🧠 Intelligent drug name correction
* ⚠️ Drug interaction detection (Low / Moderate / High)
* 🚨 High-risk alert system
* 🌐 Graph visualization of drug conflicts

---

## 🛠️ Tech Stack

* **Python**
* **NetworkX** (Graph visualization)
* **Matplotlib** (Plotting)
* **Pandas** (Data handling)
* **Difflib** (Fuzzy matching)

---

## 🔄 Workflow

Encrypted Input
⬇
Decryption (Caesar Cipher)
⬇
Drug Name Correction
⬇
Interaction Detection
⬇
Risk Analysis
⬇
Graph Visualization

---

## 🧪 Example

### 🔐 Input (Encrypted)

```
Sdudfhwdpro, Lehsurihq, Dvslulq
```

### 🔓 Decrypted

```
Paracetamol, Ibuprofen, Aspirin
```

### ⚠️ Detected Interactions

* Paracetamol + Ibuprofen → Moderate
* Paracetamol + Aspirin → Low
* Ibuprofen + Aspirin → 🚨 High

---

## 📊 Output

* ✅ Corrected drug names
* 📊 Interaction table
* 🚨 High-risk alerts
* 🌐 Visual interaction graph

---

## 🏆 Impact

This system helps:

* Prevent harmful drug combinations
* Assist pharmacists and healthcare providers
* Improve patient safety using automation

---

## 📌 Future Improvements

* Integration with real-world drug databases (e.g., DrugBank API)
* Web-based dashboard for hospitals
* Patient history tracking
* Automated prescription scanning

---

## 👨‍💻 Authors

* Saghana M
* Shethu RS
* Varsha S
* Abinaya R

---

## 📢 Conclusion

The Pharmaceutical Interaction Engine demonstrates how **AI, cryptography, and graph analysis** can work together to solve real-world healthcare problems and prevent critical medical errors.
