<div align="center">
<h1 align="center" style="border: none; margin: 10px; font-size: 3.5rem;">🍀Q U E S T I O N --V A U L T</h1>
  <br/>

  <p>
    <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
    <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
    <img src="https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=sqlite&logoColor=white" />
  </p>

  <p><b>A robust, server-side archive engineered to manage, query, and serve academic resources with precision.</b></p>

  ---
</div>

## 🛡️ The Architecture

The **Question Vault** is built on the philosophy of **Reliability** and **Schema Integrity**. Moving beyond simple file storage, this implementation uses a relational database to map subjects, years, and departments into a queryable academic network.

### ⚙️ Core Engine:
- **Django Framework:** Handling the heavy lifting of routing, authentication, and file serving.
- **Relational SQL:** A structured database designed for complex filtering (find any paper by subject code, semester, or year instantly).
- **Secure Storage:** Managed handling of academic PDFs and documents.

---

## 🚀 System Capabilities

<table border="0">
  <tr>
    <td width="50%">
      <img src="https://img.icons8.com/fluency/100/000000/database.png" width="45px" />
      <h3>Relational Mapping</h3>
      <p>Custom SQL models link question papers to specific MAKAUT regulations and curricula.</p>
    </td>
    <td width="50%">
      <img src="https://img.icons8.com/fluency/100/000000/api.png" width="45px" />
      <h3>Django REST Logic</h3>
      <p>Clean API endpoints providing structured JSON data for frontend consumers.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="https://img.icons8.com/fluency/100/000000/admin-settings-male.png" width="45px" />
      <h3>Admin Control</h3>
      <p>Leveraging Django's powerful admin suite for effortless content moderation.</p>
    </td>
    <td width="50%">
      <img src="https://img.icons8.com/fluency/100/000000/search-database.png" width="45px" />
      <h3>Advanced Querying</h3>
      <p>Optimized SQL lookups to ensure the vault remains fast even as thousands of papers are added.</p>
    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack

<div align="left">
  <img src="https://skillicons.dev/icons?i=py,django,postgres,sqlite,bash,docker,github,postman" />
</div>

---

## 📂 Project Blueprint

```text
question_vault/
├── 📁 core/               # Project Settings & Config
├── 📁 papers/             # Main App: Models, Views, Admin
│   ├── 📄 models.py       # SQL Schema Definition
│   ├── 📄 views.py        # Request Handling Logic
│   └── 📄 serializers.py  # Data Formatting
├── 📁 media/              # Stored PDFs & Assets
├── 📄 manage.py           # Django CLI
└── 📄 requirements.txt    # Python Dependencies
```
<hr/>

<h2>🧠 Design Philosophy</h2>

<p>
<b>Question Vault</b> is engineered with a simple belief:
academic data deserves structure, not chaos.
</p>

<p>
Instead of dumping PDFs into folders, this system models real-world
academic relationships using a relational database. Subjects, semesters,
departments, regulations, and years are first-class entities, not filenames.
</p>

<p>
This approach enables deterministic queries, long-term scalability,
and clean data integrity across the entire archive.
</p>

<hr/>

<h2>⚙️ How It Works</h2>

<ul>
  <li>📄 Academic papers are uploaded via Django-backed endpoints</li>
  <li>🧬 Metadata is normalized into SQL models</li>
  <li>🔍 Queries are executed using indexed relational lookups</li>
  <li>📦 PDFs are served securely through Django’s media handling</li>
</ul>

<p>
The result is a backend that behaves more like a search engine than a file cabinet.
</p>

<hr/>

<h2>🚀 Features Overview</h2>

<ul>
  <li>✅ Structured storage of question papers</li>
  <li>✅ Department, semester, year, and subject-based filtering</li>
  <li>✅ Django Admin dashboard for easy moderation</li>
  <li>✅ REST-ready architecture for frontend integration</li>
  <li>✅ Scales cleanly as the archive grows</li>
</ul>
<h2>🧪 Local Setup</h2>

<pre>
git clone https://github.com/Puskar2Sora/question-vault.git
cd question-vault
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
</pre>

<p>
Open <code>http://127.0.0.1:8000/</code> to access the application locally.
</p>

<hr/>

<h2>🎯 Use Cases</h2>

<ul>
  <li>🏫 University question paper repositories</li>
  <li>📚 Exam preparation platforms</li>
  <li>🗂️ Department-wise academic archives</li>
  <li>🏛️ Internal institutional resource systems</li>
</ul>

<hr/>

<h2>🔒 Strengths</h2>

<ul>
  <li>Schema-first backend design</li>
  <li>Clean separation of data and files</li>
  <li>Admin-friendly content management</li>
  <li>Production-grade Django patterns</li>
</ul>

<hr/>

<h2>📌 Future Enhancements</h2>

<ul>
  <li>🔐 Role-based access control</li>
  <li>⚡ Advanced search & filtering</li>
  <li>📊 Analytics on paper usage</li>
  <li>🌐 Frontend integration</li>
</ul>

<hr/>

<h2>🤝 Contributions</h2>

<p>
Contributions, ideas, and improvements are welcome.
Fork the repository, create a feature branch, and submit a pull request.
</p>

<hr/>

<h2>📜 License</h2>

<p>
This project is open-source and available under the MIT License.
</p>

<hr/>

<p align="center">
Built with discipline, structure, and curiosity ☘️<br/>
Designed for developers. Built for scale.
</p>
