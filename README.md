<<<<<<< HEAD
# **RemoteOK Job Scraper + Excel Report + Email Automation**

A simple Python automation script that fetches job postings from the **RemoteOK API**, exports them to an Excel file, and sends them as an email attachment.

## 🚀 Features

* Fetches fresh job listings from RemoteOK
* Converts API data into a structured Excel file (`remoteok_jobs.xls`)
* Handles nested JSON fields safely
* Sends the Excel file via Gmail using SMTP
* Clean, modular code with functions

---

## 🛠 Tech Stack

* Python
* requests
* xlwt
* smtplib
* email.mime
* Gmail App Password

---

## 📦 Installation

```bash
git clone 
cd 
pip install -r requirements.txt
```

---

## ▶️ Usage

```bash
python remoteok_scrapper.py
```

The script will:

1. Fetch job postings
2. Save `remoteok_jobs.xls`
3. Email the file to your defined recipients

---

## 🔐 Gmail Setup

To use Gmail SMTP you must create an **App Password**:

1. Go to Google Account → Security
2. Enable *2-Step Verification*
3. Create **App Password**
4. Use it in your script:

```python
smtp.login(email, "your_app_password_here")
```

---

## 📁 Output File

```
remoteok_jobs.xls
```

Contains all job fields, including lists/dicts converted to safe strings.

---

## 🧩 Sample Code Snippet

```python
json_data = get_job_postings()[1:]
output_jobs_to_xls(json_data)
send_email(...)
```

---
=======
# **RemoteOK Job Scraper + Excel Report + Email Automation**

A simple Python automation script that fetches job postings from the **RemoteOK API**, exports them to an Excel file, and sends them as an email attachment.

## 🚀 Features

* Fetches fresh job listings from RemoteOK
* Converts API data into a structured Excel file (`remoteok_jobs.xls`)
* Handles nested JSON fields safely
* Sends the Excel file via Gmail using SMTP
* Clean, modular code with functions

---

## 🛠 Tech Stack

* Python
* requests
* xlwt
* smtplib
* email.mime
* Gmail App Password

---

## 📦 Installation

```bash
git clone 
cd api_scrapper
pip install -r requirements.txt
```

---

## ▶️ Usage

```bash
python remoteok_scrapper.py
```

The script will:

1. Fetch job postings
2. Save `remoteok_jobs.xls`
3. Email the file to your defined recipients

---

## 🔐 Gmail Setup

To use Gmail SMTP you must create an **App Password**:

1. Go to Google Account → Security
2. Enable *2-Step Verification*
3. Create **App Password**
4. Use it in your script:

```python
smtp.login(email, "your_app_password_here")
```

---

## 📁 Output File

```
remoteok_jobs.xls
```

Contains all job fields, including lists/dicts converted to safe strings.

---

## 🧩 Sample Code Snippet

```python
json_data = get_job_postings()[1:]
output_jobs_to_xls(json_data)
send_email(...)
```

---

>>>>>>> 2b45892a4700847ca41141bc006e38f784fe2922
