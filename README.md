# awscloudresume
# 🧠 Sudharsan V — AWS Cloud Resume Challenge 🔥

Welcome to the **legendary serverless resume** built to **flex cloud skills** and trigger an existential crisis in my haters.

## ⚙️ What This Is

This isn't *just* a resume — it's a **full-stack AWS-powered application**, built to show I'm not just in the cloud...  
**I *am* the cloud.**

Live site → [https://sudharsan17.online](https://sudharsan17.online)

---

## 🧩 Built With

| Tech Stack | Purpose |
|------------|---------|
| 🗂️ **S3** | Static site hosting |
| 🌍 **CloudFront** | Global distribution + HTTPS |
| 🌐 **Route 53** | Custom domain DNS |
| ⚡ **Lambda (Node.js)** | Serverless compute for visitor count |
| 🧬 **DynamoDB** | NoSQL DB to track visitor hits |
| 🚀 **API Gateway** | HTTP API to expose Lambda |
| 🛠️ **HTML/CSS/JS** | Modified HTML5 UP Dimension template |
| 🧪 **Custom JS** | Live visitor counter with `fetch()` |

---

## 🧠 Features

- 🚀 **Live Serverless Visitor Counter** (No `countapi.xyz`, all AWS)
- 🌌 **Dark Nebula Background** to add mystique
- 🎖️ **Auto-scrolling AWS Badge Slider**
- 🧊 **CloudFront-powered CDN** with custom domain: `sudharsan17.online`
- 📈 Fully integrated with Git for versioning
- 🔥 Looks amazing on desktop & mobile — tested by fire

---

## 🛠️ Serverless Counter Stack

- `DynamoDB` → Table: `visitorcount`  
- `Lambda` → Node.js function that `GetItem` + `PutItem`  
- `API Gateway` → GET `/visitorcounter` endpoint  
- `CORS` handled like a boss

---

## 📂 File Structure Highlights

```bash
/
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── index.html
├── GUIDENCE.txt    # Full AWS Build Walkthrough
└
