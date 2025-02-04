# PDF Splitter & Merger

## Project Overview
The **PDF Splitter & Merger** is a web-based tool that allows users to:
- **Split** a PDF file into individual pages or select specific pages to extract.
- **Merge** multiple PDF files into a single document.

This project is built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js) and is hosted on Render.


---

##  Features
✅ Upload a PDF file to split or merge.<br>
✅ **Split PDFs** by selecting specific pages for extraction.<br>
✅ **Merge multiple PDFs** into a single document.<br>
✅ Download the processed PDF after splitting or merging.<br>
✅ Error handling for invalid files or incorrect operations.<br>

---

##  Tech Stack
- **Frontend**: React.js (Vite) + Tailwind CSS
- **Backend**: Node.js + Express.js
- **Database**: MongoDB Atlas
- **Storage**: Multer for file handling
- **PDF Processing**: pdf-lib

---

##  Project Structure
```
📦 pdf-splitter-merger
 ┣ 📂 frontend (React.js Vite)
 ┣ 📂 backend (Node.js, Express.js)
 ┣ 📜 .gitignore
 ┣ 📜 package.json
 ┣ 📜 README.md
```

---

##  How to Run Locally

### Clone the Repository
```bash
git clone https://github.com/alimunfeddev/pdf-splitter-merger.git
cd pdf-splitter-merger
```

### Install Dependencies
#### Backend Setup:
```bash
cd backend
npm install
```
#### Frontend Setup:
```bash
cd ../frontend
npm install
```

### Start the Application
#### Start Backend Server:
```bash
cd backend
npm start
```
#### Start Frontend Server:
```bash
cd frontend
npm run dev
```

The application should now be running at `http://localhost:5173/`.

---

##  Error Handling & Validations
- Ensures only **valid PDF files** are uploaded.
- Handles large file uploads gracefully.
- Provides error messages for unsupported actions.

---

##  Contributing
Contributions are welcome! Feel free to **fork**, create a new branch, and submit a **pull request**.

---

##  License
This project is licensed under the **MIT License**.

---

##  Contact
For any queries or feedback, email at **alimunfed17@gmail.com**