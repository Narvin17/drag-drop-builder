# Drag & Drop Website Builder

A complete web application for building websites using drag-and-drop interface.

## Features

- 🎨 Drag and drop components (Text, Button, Image, Card, Form)
- ⚙️ Edit component properties (text, colors, sizes)
- 💾 Save and load page layouts
- 📤 Export pages as HTML/CSS
- 🔄 Real-time preview
- 💎 Clean, modern UI

## Tech Stack

**Frontend:**
- React 18
- Tailwind CSS
- Vite

**Backend:**
- Python FastAPI
- SQLite Database
- CORS enabled

## Quick Start

### Prerequisites
- Node.js 16+
- Python 3.8+
- Git

### Backend Setup

```bash
cd backend
python -m venv venv

# Windows
venv\Scripts\activate

# Mac/Linux
source venv/bin/activate

pip install -r requirements.txt
python main.py
```

Backend runs on: `http://localhost:8000`

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on: `http://localhost:5173`

## Usage

1. Open http://localhost:5173 in your browser
2. Drag components from the toolbar to the canvas
3. Click on components to edit their properties
4. Click "Save Page" to save your design
5. Click "Export HTML" to download your page

## API Endpoints

- `POST /api/pages` - Create a new page
- `GET /api/pages/{page_id}` - Get page data
- `PUT /api/pages/{page_id}` - Update page
- `DELETE /api/pages/{page_id}` - Delete page
- `POST /api/export/{page_id}` - Export as HTML
- `GET /api/pages` - List all pages

## License

MIT - Free to fork and sell
