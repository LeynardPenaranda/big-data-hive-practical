# Big Data Hive Practical

Welcome to the **Big Data Hive Practical** repository! 🚀  
This collection of hands-on exercises and practical examples demonstrates how to use **Apache Hive** for data analysis and querying.

This project is aimed at helping you understand:

- 🧑‍💻 Querying with HiveQL (HQL)  
- 🔄 Data Management in Hive  
- 📊 CRUD Operations in Hive    

---

## 🖥️ Setting up Hive

### 🔹 Opening Hive CLI in Dataproc Terminal
The first step in working with Apache Hive is opening the Hive Command Line Interface (CLI). In this project, we'll be using the **Dataproc terminal** to open Hive and perform our tasks.

<p align="center">
  <img src="https://github.com/LeynardPenaranda/big-data-hive-practical/blob/main/images/opening%20hive%20in%20dataproc%20-%20cluster%20terminal.png" width="900" alt="Opening Hive in Dataproc Terminal">
</p>

---

### 🔹 Creating a Database and Table in Hive CLI
Once Hive CLI is opened, you can create a database and a table. In this step, we will be using the **Hive CLI** to create a database and then show how to create a table within that database.

<p align="center">
  <img src="https://github.com/LeynardPenaranda/big-data-hive-practical/blob/main/images/show%20and%20create%20database%20in%20hive.png" width="900" alt="Creating Database and Table in Hive">
</p>

---

## 🔑 Using Beeline CLI to Connect to Hive

### 🔹 Connecting to Hive via Beeline CLI
Beeline is an alternative to the Hive CLI and allows us to connect to Hive using JDBC. In this step, we will use **Beeline** to open Hive and then connect it to the Hive server using JDBC.

<p align="center">
  <img src="https://github.com/LeynardPenaranda/big-data-hive-practical/blob/main/images/using%20beeline%20to%20open%20hive%20and%20connecting%20it%20first%20to%20hive%20server.png" width="900" alt="Connecting Hive with Beeline">
</p>

---

### 🔹 Querying in Beeline After Connection
After connecting to Hive via Beeline, you can run queries just like in Hive CLI. For example, here is how to use **Beeline** to query Hive databases.

<p align="center">
  <img src="https://github.com/LeynardPenaranda/big-data-hive-practical/blob/main/images/after%20beeline%20connected%20to%20hive%20server%20we%20can%20now%20do%20sql%20query%20such%20as%20show%20databases%3B.png" width="900" alt="Querying Hive in Beeline">
</p>

---

### 🔹 Creating a Table in Beeline
Once connected, we can create tables in Beeline using **HiveQL** syntax.

<p align="center">
  <img src="https://github.com/LeynardPenaranda/big-data-hive-practical/blob/main/images/created%20a%20customer%20table%20in%20beeline.png" width="900" alt="Creating a Table in Beeline">
</p>

---

## 🛠️ Application Type in Hive

### 🔹 Showing the Application Type of Hive
You can also check and configure the **application type** for the Hive environment. This helps ensure Hive operates as expected in your system configuration.

<p align="center">
  <img src="https://github.com/LeynardPenaranda/big-data-hive-practical/blob/main/images/This%20shows%20the%20application%20type%20of%20the%20hive.png" width="900" alt="Hive Application Type">
</p>

---

## 🔄 Performing CRUD Operations in Hive

### 🔹 Doing CRUD Operations in Hive
Keep in mind that **Hive** is primarily a data warehouse solution and is not optimized for performing fast CRUD (Create, Read, Update, Delete) operations. These operations can take a while because Hive is more focused on data analysis rather than transactional tasks.

<p align="center">
  <img src="https://github.com/LeynardPenaranda/big-data-hive-practical/blob/main/images/doing%20CRUD%20in%20hive%20will%20take%20some%20time.png" width="900" alt="CRUD Operations in Hive">
</p>

---

## 🗃️ Hive Metastore in MySQL

### 🔹 Accessing the Metastore in MySQL
Hive uses a **Metastore** to manage its metadata. The Metastore can be stored in **MySQL** for more efficient management and access. Here’s how to access the **Hive Metastore** in MySQL.

<p align="center">
  <img src="https://github.com/LeynardPenaranda/big-data-hive-practical/blob/main/images/metastore%20in%20mysql.png" width="900" alt="Hive Metastore in MySQL">
</p>

---

### 🔹 Inside the Metastore Table
Here’s a look at the **Metastore** table that stores metadata information for your Hive environment.

<p align="center">
  <img src="https://github.com/LeynardPenaranda/big-data-hive-practical/blob/main/images/inside%20the%20metastore%20table.png" width="900" alt="Inside the Metastore Table">
</p>

---

## 💡 Additional Notes

- **Hive CLI** vs **Beeline**: Both tools allow you to query Hive, but Beeline is generally preferred for better performance and stability, especially when connecting through JDBC.
- **CRUD Operations in Hive**: Hive is not designed for transactional data or frequent updates, so these operations may take longer to execute compared to traditional databases.
- **Hive Metastore**: The Metastore is crucial for maintaining metadata information about the tables and schemas in Hive.

---

Feel free to check out the code and other exercises in this repository for further details on working with Hive for Big Data applications. Happy querying! 🎉
