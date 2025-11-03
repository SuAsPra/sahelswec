# 🌍 Sahel Women Education Connect (SWEC)

**Sahel Women Education Connect (SWEC)** is a grassroots initiative dedicated to empowering conflict-affected and vulnerable women and girls of the Sahel regions of Cameroon and beyond.

---

## 🕊️ Mission
To empower women and youth through education, leadership, and socio-educational programs, enabling them to participate fully in community development and contribute to building a sustainable future.

This repository is made for the **SWEC organisation**, hosted on Render:  
🔗 [https://swecafrica-org.onrender.com](https://swecafrica-org.onrender.com)

---

## 🧩 Features
- Informative homepage introducing SWEC’s mission and purpose  
- Dedicated pages for:
  - **Home (index.html):** Overview of the organization  
  - **About Us:** Founders, funders, and partners  
  - **Projects:** Details of SWEC’s ongoing initiatives  
  - **Contact:** Communication and outreach information  
- Responsive layout for desktop and mobile devices  
- Simple and accessible design following NGO website best practices  

---

## 🔄 Dynamic Community Updates (Google Forms + Google Sheets Integration)
The **Projects** page includes a dynamic “Community Updates” section that automatically loads new project entries from a **Google Form → Google Sheet** integration.  

This allows SWEC team members (non-developers) to regularly add new projects without editing the website manually.  
- Project data (title, date, description, author) and optional image links are submitted through a Google Form.  
- The data is stored in a connected Google Sheet.  
- A **Google Apps Script** converts the sheet into a JSON API endpoint.  
- The site dynamically fetches and displays the latest projects **above the static ones** each time the page is loaded.  
- Google Drive image links are automatically converted for web visibility.

This makes the website **self-updating and low-maintenance**, even without developer access.

---

## 🛠️ Tech Stack
- **HTML5**  
- **CSS3**  
- **JavaScript (Dynamic data loading via Fetch API)**
- **Responsive Design** (Flexbox / Media Queries)
- **Google Apps Script (for live data API)**
- **Static Hosting (Render)**

---

## 📁 Folder Structure
SWEC/
│
├── index.html
├── about.html
├── projects.html
├── contact.html
│
├── assets/
│ ├── banner.jpg
│ ├── logo.jpg (many more images)
│
└── css/
└── style.css

## 🚀 Setup Instructions
1. Clone the repository  
   ```bash
   git clone https://github.com/<your-username>/swec.git
The repository is already hosted as a website in render. The render account used for hosting is private and uses the free version. However if you are to change the contents of the website then it is advisable to create a new render account and host in it or contact the repository owner to redeploy or provide access to hosting platform. 
