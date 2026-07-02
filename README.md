<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1B2A,100:1B6CA8&height=120&section=header"/>
<div align="start">
  
## About Me

Hello! My name is **Jonathan**, I am a systems analyst and developer in training. I am constantly learning and improving my skills in **FullStack** development, seeking to create modern and efficient solutions.

- 🎓 Student of Software Analysis and Development
- 🚀 Always seeking new challenges, knowledge, and skills
- 📫 Contact: jonathanuber121207@gmail.com

</div>

<br>

<div align="start">

## Learning Technologies

<div align="start" style="display: inline_block">

### Back-End

![Java](https://img.shields.io/badge/java-414245.svg?style=for-the-badge&logo=openjdk&logoColor=ED8B00) ![Spring](https://img.shields.io/badge/spring-414245.svg?style=for-the-badge&logo=spring&logoColor=6DB33F) ![Python](https://img.shields.io/badge/python-414245?style=for-the-badge&logo=python&logoColor=3776AB)  ![Flask](https://img.shields.io/badge/flask-414245.svg?style=for-the-badge&logo=flask&logoColor=white)  ![R](https://img.shields.io/badge/r-414245.svg?style=for-the-badge&logo=r&logoColor=276DC3) ![C](https://img.shields.io/badge/C-414245?style=for-the-badge&logo=c&logoColor=00599C)

<div align="start" style="display: inline_block">
  
### Front-End

![HTML5](https://img.shields.io/badge/html5-414245.svg?style=for-the-badge&logo=html5&logoColor=E34F26) ![CSS3](https://img.shields.io/badge/css3-414245.svg?style=for-the-badge&logo=css3&logoColor=1572B6)  ![JavaScript](https://img.shields.io/badge/javascript-414245.svg?style=for-the-badge&logo=javascript&logoColor=F7DF1E) ![TypeScript](https://img.shields.io/badge/TypeScript-414245?style=for-the-badge&logo=typescript&logoColor=3178C6)  ![Next](https://img.shields.io/badge/Next-414245?style=for-the-badge&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/React-414245?style=for-the-badge&logo=react&logoColor=61DAFB) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-414245?style=for-the-badge&logo=tailwindcss&logoColor=06B6D4) ![Figma](https://img.shields.io/badge/figma-414245.svg?style=for-the-badge&logo=figma&logoColor=F24E1E) 

<div align="start" style="display: inline_block">

### Databases
  
![MySQL](https://img.shields.io/badge/mysql-414245.svg?style=for-the-badge&logo=mysql&logoColor=white) ![PostegreSQL](https://img.shields.io/badge/PostgreSQL-414245?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/Sqlite-414245?style=for-the-badge&logo=sqlite&logoColor=003B57) ![Cassandra](https://img.shields.io/badge/cassandra-414245.svg?style=for-the-badge&logo=apache-cassandra&logoColor=1287B1) 


<div align="start" style="display: inline_block">

### Other Technologies

![Kotlin](https://img.shields.io/badge/Kotlin-414245?&style=for-the-badge&logo=kotlin&logoColor=blue) ![Git](https://img.shields.io/badge/git-414245.svg?style=for-the-badge&logo=git&logoColor=F05032) ![Docker](https://img.shields.io/badge/Docker-414245?style=for-the-badge&logo=docker&logoColor=2496ED) 	![Fedora](https://img.shields.io/badge/Fedora-414245?style=for-the-badge&logo=fedora&logoColor=294172) ![Power Bi](https://img.shields.io/badge/power_bi-414245?style=for-the-badge&logo=powerbi&logoColor=F2C811) ![Node-RED](https://img.shields.io/badge/Node--RED-414245.svg?style=for-the-badge&logo=node-red&logoColor=8F0000) ![Postman](https://img.shields.io/badge/Postman-414245.svg?style=for-the-badge&logo=Postman&logoColor=FF6C37)
  
</div>

<br>

---

## Personal Projects

### [Documental Assessoria Imobiliária](https://www.linkedin.com/posts/jonathan-luis-uber_desenvolvimentodesoftware-saas-java-ugcPost-7462116265973862400-bPd0/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFQttCcB6fjZsD8cPYk2_BWGUb-rDGfp0L0)
**Project Overview:**  
A real estate advisory platform designed to professionalize document operations and improve the end-to-end service workflow for clients and internal staff.

**Business Context & Challenge:**  
The operation depended on fragmented communication and manual tracking, creating bottlenecks in document follow-up, status visibility, and delivery consistency.

**Impact Delivered:**  
- Centralized document and process management into a single workflow.  
- Reduced operational friction by improving traceability and task organization.  
- Increased reliability in client service through clearer status control and structured handling of critical files.

**Tech Stack:**  
Java, Spring Boot, Spring Security, Spring Data JPA, React (Vite), Typescript, TailwindCSS, Postgresql (Supabase), Cloudfare R2 (Object Storage).

---

### [Time Trial](https://github.com/PabloTzeliks/time-trial-api)
*v1 delivered · remodeling in progress*

**Physical race sensors to a live leaderboard, event-driven end to end.**

A real-time IoT lap-timing platform on physical hardware (ESP32 + RFID). The team left the course's expected stack (Node-RED + MySQL) and rebuilt the problem around event-driven architecture. Demoed live to instructors and WEG IT leadership, with physical ESP32 hardware on stage.

- Edge devices kept deliberately "dumb" — they emit only `{rfid, timestamp}`; all validation lives in the backend, so sensors scale horizontally.
- Async MQTT ingestion into a running 3-node Cassandra cluster with QUORUM reads/writes; real-time output over WebSocket, history over REST.
- Python analytics — K-Means clustering, Streamlit dashboard.
- *Remodeling toward:* Kafka Streams for lap aggregation, first-class `Pista` and `Sessão` entities, durable lap-time storage.

---

### Restyle - In Development
**Project Overview:**  
Restyle is a regional marketplace for pre-owned fashion—a curated showcase connecting local buyers and sellers, featuring quick contact via WhatsApp.

**Business Context & Challenge:**  
The goal of the MVP is to prove that a storefront featuring filters, photos, and direct contact options accelerates the sale of used parts compared to informal listings.

Product direction:

- Regional marketplace (Jaraguá do Sul and surrounding area)
- No integrated payment — transactions take place off-platform
- No internal chat — contact via WhatsApp
- Open registration for buyers; sellers admitted via admin approval
- Categories and cities managed within the system

**Impact Delivered:**  
- Facilitates the sale of used or pre-owned parts and products
- Eliminates fees and reduces bureaucracy for the purchase and sale of used and pre-owned parts.

**Tech Stack:**  
Next.js, Typescript, TailwindCSS, Postresql (Supabase), Redis,  Shadcn, Lucide Icons, GSAP, Cloudfare R2 (Object Storage), Prisma, Next Auth.

---

### [SAMG-SM (Final High School Project)](https://www.linkedin.com/posts/jonathan-luis-uber_ti-tecnologia-desenvolvimentodesistemas-ugcPost-7426772651865681920-E9TM/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFQttCcB6fjZsD8cPYk2_BWGUb-rDGfp0L0)
**Project Overview:**  
Think of each maintenance room as a "household." Just like at home, we use cleaning supplies, food (lunches), and other materials. The goal of this project is to create a smart system to track everything that comes in, goes out, and is spent in each of these "households."

Instead of relying on paper notes or complicated spreadsheets, we will have an organized tool to know exactly:

- **What we have:** How many cleaning products or breakroom items remain in stock.
- **Who used it:** Which maintenance room consumed a specific material.
- **How ​​much it cost:** The total expenditure on materials for the Room A team, for example.

**Business Context & Challenge:**  
Develop an administrative system to efficiently manage all cleaning supplies, food items, and other consumables, as well as to track specific expenses by maintenance room, ensuring organization, cost savings, and transparency in resource utilization.

**Impact Delivered:**  
- Inventory Control – Record and monitor the inflow and outflow of cleaning supplies and food items.
- Consumption Management – ​​Track the quantity of supplies used in each maintenance room.
- Financial Control – Generate detailed expenditure reports by room, period, and product category.
- Transparency and Waste Reduction – Identify excessive consumption and propose optimization measures.
- Automation – Minimize manual processes using smart spreadsheets or a web-based system.

**Tech Stack:**  
Python, Flask, HTML, TailwindCSS, JavaScript, Postgresql (Render), plus server-side validation and template rendering.

---

 ## Contact
 
<div> 
  <a href="https://instagram.com/jonathan7_gb" target="_blank"><img src="https://img.shields.io/badge/-Instagram-414245?style=for-the-badge&logo=instagram&logoColor=E4405F" target="_blank"></a>
  <a href = "mailto:jonathanuber121207@gmail.com" target="_blank"><img src="https://img.shields.io/badge/-Gmail-414245?style=for-the-badge&logo=gmail&logoColor=D14836" target="_blank"></a>
</div>
</div>

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=0:1B6CA8,100:0D1B2A&height=120&section=footer"/>
