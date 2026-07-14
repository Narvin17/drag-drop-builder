# Drag & Drop Website Builder v2.0

A complete, production-ready web application for building websites using drag-and-drop interface.

## ✨ Features

- 🎨 **Drag and Drop** - Easily drag components onto the canvas
- ⚙️ **Property Editor** - Edit colors, sizes, text, fonts, padding, border radius
- 💾 **Save & Load** - Save unlimited pages to database
- 📤 **Export** - Download pages as standalone HTML files
- 📚 **Page Manager** - View, load, and delete saved pages
- 📊 **Statistics** - Track total pages and templates
- 🎯 **5 Components** - Text, Button, Image, Card, Input
- 🔄 **Real-time Preview** - Live preview of your design
- 🌐 **Full CORS Access** - Works with any frontend
- 📁 **File Upload** - Upload and manage assets
- 🎭 **Template System** - Save and reuse designs

## 🛠 Tech Stack

**Frontend:**
- React 18
- Tailwind CSS
- Vite (blazing fast)

**Backend:**
- Python FastAPI
- SQLite Database
- CORS enabled

## 🚀 Quick Start

### Prerequisites
- Node.js 16+ ([Download](https://nodejs.org/))
- Python 3.8+ ([Download](https://www.python.org/))
- Git ([Download](https://git-scm.com/))

### 1️⃣ Backend Setup (Python)

```bash
cd backend
python -m venv venv

# Windows:
venv\Scripts\activate

# Mac/Linux:
source venv/bin/activate

pip install -r requirements.txt
python main.py
```

✅ Backend runs on: `http://localhost:8000`

### 2️⃣ Frontend Setup (React) - NEW TERMINAL

```bash
cd frontend
npm install
npm run dev
```

✅ Frontend opens at: `http://localhost:5173`

## 💡 How to Use

1. **Add Components** - Click buttons in the left toolbar
2. **Drag & Position** - Drag components around the canvas
3. **Edit Properties** - Click component, edit in the right panel
4. **Save Page** - Click "Save" to store in database
5. **Export HTML** - Click "Export" to download as HTML file
6. **Manage Pages** - Click "Pages" to view all saved pages

## 📡 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/pages` | Create new page |
| GET | `/api/pages` | List all pages |
| GET | `/api/pages/{id}` | Get page details |
| PUT | `/api/pages/{id}` | Update page |
| DELETE | `/api/pages/{id}` | Delete page |
| POST | `/api/export/{id}` | Export as HTML |
| GET | `/api/stats` | Get builder statistics |
| POST | `/api/upload` | Upload file |

## 🎯 Component Types

- **Text** - Add and style text
- **Button** - Create interactive buttons
- **Image** - Add images with custom sizing
- **Card** - Container with border and padding
- **Input** - Add form input fields

## 🎨 Customization Options

For each component, you can customize:
- 🖌️ **Background Color** - Component background
- 📝 **Text Color** - Font color
- 📏 **Font Size** - Text size in pixels
- 📐 **Width & Height** - Component dimensions
- 🔲 **Padding** - Inner spacing
- 🔘 **Border Radius** - Corner roundness
- 📍 **Position** - Drag and drop placement

## 📦 Project Structure

```
drag-drop-builder/
├── backend/
│   ├── main.py              # FastAPI server
│   ├── requirements.txt      # Python dependencies
│   └── database.db          # SQLite database
├── frontend/
│   ├── src/
│   │   ├── App.jsx          # Main app
│   │   ├── api.js           # API client
│   │   ├── components/
│   │   │   ├── Canvas.jsx
│   │   │   ├── Toolbar.jsx
│   │   │   ├── PropertyPanel.jsx
│   │   │   ├── PreviewPanel.jsx
│   │   │   └── PageManager.jsx
│   │   └── index.css
│   ├── package.json
│   └── vite.config.js
└── README.md
```

## 🚀 Deployment

### Frontend (Vercel)
```bash
cd frontend
npm run build
# Deploy the 'dist' folder to Vercel
```

### Backend (Railway / Heroku)
```bash
# Push to Heroku or Railway
```

## 📝 License

**MIT License** - Free to fork, modify, and sell!

## 🤝 Contributing

Feel free to fork and improve this project!

## 💬 Support

For issues or questions, open a GitHub issue.

---

**Built with ❤️ by Narvin17**

Happy Building! 🎉
