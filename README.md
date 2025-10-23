# NirmaanAI

NirmaanAI is an **AI-powered component generator** built using the **Google Gemini API**.  
It allows developers to **quickly generate responsive UI components** with AI assistance.

---

## 🌟 Features

- Generate React UI components automatically
- Responsive design with Tailwind CSS
- Integration with Google Gemini AI API
- Interactive editor powered by Monaco Editor
- Copy, export, and open components in a new tab

---

## 💻 Setup & Installation

1. **Clone the repository**
```bash
git clone https://github.com/AarjooKumar369/NirmaanAI.git
cd NirmaanAI
```

2. **Install dependencies**
```bash
npm install
```

3. **Add your Gemini API key**  
Create a `.env` file in the root folder:
```bash
VITE_GEMINI_API_KEY=YOUR_API_KEY_HERE
```

4. **Run the development server**
```bash
npm run dev
```

5. Open the browser at the URL shown in the terminal (usually `http://localhost:5173`).

---

## 🛠️ Usage

- Use the **AI component generator** on the home page
- Customize components via the editor
- Copy or export generated components easily

---

## 💾 Project Structure

```
src/
 ├─ components/   # Navbar, buttons, reusable UI components
 ├─ pages/        # Home page & main logic
 ├─ assets/       # Images, logos
 └─ App.jsx       # Main React app entry
```

---

## ⚡ Notes

- Make sure `.env` file is **not committed** to GitHub (add to `.gitignore`)
- Tailwind CSS is used for styling — feel free to customize colors and animations
- Monaco Editor powers the interactive code editing experience

