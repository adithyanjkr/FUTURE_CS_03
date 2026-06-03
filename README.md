# 🛡️ API Security Risk Analysis

## 📌 What is this?
* A professional **security review** of a public network platform.
* It finds **logical flaws** and translates technical risks into **plain business impacts**.
* Uses safe, **"read-only" methods** to check for data leaks without breaking anything.

## ⚙️ Project Details
* **Tested API:** `https://jsonplaceholder.typicode.com`
* **Methodology:** **Passive testing** based on industry-standard **OWASP security guidelines**.
* **Core Focus:** Checking **authentication**, **data exposure**, and **input validation** layers.

## 🛠️ Tools Used
* **Kali Linux:** The primary **operating system** environment for security testing.
* **Postman:** Used for analyzing **API endpoints**, **data responses**, and **system headers**.
* **Browser DevTools:** Used for inspecting **web traffic** and background **network activity**.

## 📂 Project Files
* **Report:** The **full analysis document**.
* **Evidence:** Verified **screenshots** of endpoints, data payloads, and system headers.

## 🔍 Found Risks
* 🔴 **High:** Flaws that let users **guess URLs** to view other people's **private data**.
* 🟡 **Medium:** System loops that **leak whole user lists** or accept **messy, broken inputs**.
* 🟢 **Low:** **High traffic limits** and background headers that **reveal software names**.

## 👤 Author
* **Adithyan.V** | **Cyber Security Researcher**
