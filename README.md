# police-complaint-management-system-using-blockchain

# 🚔 Police Blockchain Validation System  

# 📌 Project Overview  
The **Police Blockchain Validation System** is a **blockchain-driven police complaint system** with **access control mechanisms** to ensure secure, transparent, and efficient handling of **First Information Reports (FIRs)** and police complaints. The system encrypts FIRs, stores them securely on a **blockchain network**, and integrates a **public cloud** to enhance transparency while maintaining data privacy.  

# 🚀 Features  
✅ **Immutable Records**: Secure storage on the blockchain prevents tampering.  
✅ **Transparency & Trust**: Decentralized handling ensures credibility.  
✅ **Secure Access Control**: Only authorized police officers can view complaints.  
✅ **Hybrid Cloud Integration**: Ensures scalability, fault tolerance, and cost efficiency.  
✅ **RSA Encryption**: Uses **public-key cryptography** for data security.  

# 🎯 Objectives  
- Develop a **blockchain-based complaint management system**.  
- Ensure **tamper-proof storage of FIRs**.  
- Implement **role-based access control** for police officers.  
- Enhance **public trust** in law enforcement agencies.  

## ⚙️ System Requirements  

### 🔧 Hardware Requirements  
- **Processor**: Intel Core i3 or above  
- **RAM**: 8GB or more  
- **Storage**: 500GB or more  

### 💻 Software Requirements  
- **Operating System**: Windows OS  
- **Programming Language**: Java  
- **Web Technology**: Servlet, JSP  
- **Web Server**: Tomcat  
- **IDE**: Eclipse Indigo  
- **Database**: MySQL with SQLyog GUI  
- **JDBC Driver**: Type 4 Driver  

## 📌 Installation Guide  

### 1️⃣ **Install Java Development Kit (JDK)**  
Ensure **Java 8 or later** is installed. Download from [Oracle JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).  
```sh
java -version
```
If Java is not installed, install it using:  
```sh
sudo apt install openjdk-11-jdk  # For Linux  
```

### 2️⃣ **Set Up MySQL Database**  
1. Download & install **MySQL Server** from [MySQL Official Site](https://dev.mysql.com/downloads/).  
2. Open **SQLyog** or MySQL Workbench and create a new database:  
   ```sql
   CREATE DATABASE police_blockchain;
   ```
3. Import the provided SQL database file (`police_blockchain.sql`).  

### 3️⃣ **Install Apache Tomcat Server**  
1. Download Tomcat from [Apache Tomcat](https://tomcat.apache.org/download-90.cgi).  
2. Extract it and configure it in Eclipse.  

### 4️⃣ **Set Up Eclipse IDE**  
1. Install **Eclipse IDE** from [Eclipse Official Site](https://www.eclipse.org/downloads/).  
2. Install required plugins for **Servlets, JSP, and JDBC**.  
3. Open Eclipse and import the project (`File` → `Import` → `Existing Projects into Workspace`).  

### 5️⃣ **Connect Database to Java Application**  
- Update the **JDBC connection settings** in the `dbconfig.properties` file:  
  ```
  DB_URL=jdbc:mysql://localhost:3306/police_blockchain
  DB_USER=root
  DB_PASSWORD=yourpassword
  ```

### 6️⃣ **Run the Project**  
1. Start **MySQL Server**.  
2. Deploy the project on **Tomcat Server** (`Run on Server`).  
3. Access the web application at:  
   ```
   http://localhost:8080/PoliceBlockchainSystem
   ```

## 🔑 Security Mechanism  
- **RSA Encryption**  
  - Public Key: `{e, n}` (Used for encryption)  
  - Private Key: `{d, n}` (Used for decryption)  
- **Blockchain Hashing**  
  - Ensures **data integrity** using **SHA-256 hashing**.  

## 📈 Results & Conclusion  
✔ **Tamper-proof storage of police complaints**.  
✔ **Secure & transparent complaint registration**.  
✔ **Faster processing & improved law enforcement efficiency**.  

## 🔮 Future Enhancements  
🚀 **AI-Based Crime Analysis** – Automate case prioritization.  
🌍 **Cross-Jurisdiction Integration** – Connect multiple police units.  
📊 **Predictive Crime Analytics** – Use AI to prevent future crimes.  

---

## 📚 References  
1. Shivaganesh Pillai, *Online FIR Registration and SOS System*, IJEC, 2017.  
2. Omoregbe et al., *Crime Reporting Innovations*, 2019.  
3. Kormpho et al., *Smart Complaint Management System*, ICT-ISPC, 2018.  
4. Dini et al., *Implementing Blockchain for Criminal Records*, 2018.  

