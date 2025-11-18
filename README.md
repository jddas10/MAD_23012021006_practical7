# Practical 7  

## 🎯 Aim  

Develop an Android application that retrieves **Person data in JSON format** from an internet API and stores the retrieved data in an **SQLite database**.

---

## 📖 Description  

This practical demonstrates how to fetch data from an online JSON API, parse it, and store it inside **SQLite**.  
The application also displays the stored data using **RecyclerView / ListView**.

### ✔ Concepts Used in the Practical  
- **JSON Format**  
- **HttpURLConnection**  
- **CoroutineScope (IO Thread)**  
- **RecyclerView / ListView Adapter**  
- **SQLite Database (CRUD)**  
- **Serializable Class**  
- **Internet Permission in Manifest**

---

## 📌 Requirements as per Practical  

### 🧾 JSON Data  
You must generate JSON using:  
👉 https://app.json-generator.com/  

JSON Object fields include:  
- `id`  
- `Name` (first name + last name)  
- `Phone No`  
- `Email`  
- `Address`  
- `Latitude`  
- `Longitude`
    
---
Also ensure:  
✔ `Person : Serializable`  

---

## 📝 App Flow  

### 1️⃣ MainActivity UI  
- Button: **Fetch Data**  
- Button: **Load From Database**  
- RecyclerView/ListView: To display stored Person data  

### 2️⃣ HttpRequest Class  
Handles:  
- API connection  
- `HttpURLConnection`  
- `GET` request  
- Returning JSON string  

### 3️⃣ JSON Parsing  
- Using `JSONObject`, `JSONArray`, or Kotlin serialization  
- Convert JSON into `Person` objects  

### 4️⃣ SQLite Database  
Store Person Data locally:  

- Insert  
- Retrieve  
- Display through RecyclerView  

---

## 📸 Screenshots with Description  

| Screenshot | Description |
|------------|-------------|
| <p align="center"/><img src="screenshots/json.jpeg" alt="Main Screen" width="250"/> | **Main Screen** contains buttons to fetch JSON data from web API and view stored data in RecyclerView. |

---

## 🛠 Key Features Implemented  

✔ Fetch JSON data from web API  
✔ Parse JSON into Person objects  
✔ Store Person data in SQLite  
✔ Display stored data using RecyclerView/ListView  
✔ Internet Permission added in AndroidManifest  
✔ Serializable class for transferring objects  

---

## 🧪 Result  

The Android application was successfully developed to:  
- Retrieve JSON data from a web API  
- Parse and convert into Person model class  
- Store data in SQLite  
- Display it using RecyclerView/ListView  

---

## 📘 Student Details  

> **Name:** *DAVE JAYDATT*  
> **Enrollment:** *23012021006*  
> **Batch:** *5IT-B-1*  
