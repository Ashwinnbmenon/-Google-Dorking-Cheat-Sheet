# -Google-Dorking-Cheat-Sheet


A powerful and clean **Google Dorks Cheat Sheet** formatted perfectly as a `README.md` for GitHub uploads.

A clean, well‑structured Google Dorks cheat sheet perfect for GitHub uploads.

---

## 📌 **Basic Operators**

| Operator    | Description                               | Example              |
| ----------- | ----------------------------------------- | -------------------- |
| `site:`     | Search within a specific domain           | `site:github.com`    |
| `inurl:`    | Results containing specific text in URL   | `inurl:login`        |
| `intitle:`  | Results containing specific text in title | `intitle:"index of"` |
| `intext:`   | Search for keywords in page body          | `intext:"password"`  |
| `filetype:` | Search for specific file extension        | `filetype:pdf`       |
| `ext:`      | Same as filetype                          | `ext:sql`            |
| `cache:`    | View Google cached version of site        | `cache:example.com`  |
| `related:`  | Websites related to target                | `related:google.com` |
| `*`         | Wildcard keyword                          | `"ethical * course"` |

---

## 🗂️ **Directory Listing Dorks**

```
intitle:"index of" password
intitle:"index of" /admin
intitle:"index of" "backup"
```

---

## 🔑 **Login Pages / Admin Panels**

```
inurl:admin
inurl:adminlogin
inurl:wp-admin
intitle:"admin login"
```

---

## 🛢️ **Database Files Exposure**

```
filetype:sql "password"
filetype:db "admin"
filetype:bak
```

---

## 🔐 **Sensitive Information Exposure**

```
filetype:log password
intext:"login failed"
filetype:env DB_USERNAME
```

---

## 👤 **Credentials / Config Files**

```
filetype:env
filetype:ini
filetype:conf
filetype:cfg
```

---

## 💾 **Backup & Old Files**

```
filetype:bak
filetype:old
filetype:backup
```

---

## 📷 **Camera / Device Feeds**

```
inurl:/view.shtml
intitle:"live view" camera
inurl:"/webcam.html"
```

---

## 🧾 **Documents (PDF, DOCX, XLSX)**

```
filetype:pdf "confidential"
filetype:xlsx password
filetype:docx "employee"
```

---

## 🛠️ **Vulnerable Software / Exposed Panels**

```
inurl:"phpinfo.php"
intext:"Apache2 Ubuntu Default Page"
intitle:"Dashboard" "Grafana"
```

---

## 🌐 **Email Harvesting Dorks**

```
"@gmail.com" site:in
"@company.com" filetype:xls
```

---

## 🧨 **Bug Bounty Focused Dorks**

```
site:target.com "index of"
site:target.com filetype:json
site:target.com inurl:dev
site:target.com inurl:test
```

---

## ⚠️ Disclaimer

This cheat sheet is **for educational and cybersecurity learning purposes only.** Do not misuse Google Dorks for unauthorized access.

---
