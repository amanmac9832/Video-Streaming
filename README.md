# Video-Streaming

Video-Streaming is a simple, elegant video streaming and upload platform built with **FastAPI** and **Supabase Storage**. Users can upload, view, stream, and delete videos through a clean UI. Ideal for lightweight content management and learning cloud-based storage integration.

---

## 🔧 Tech Stack

- **Backend**: FastAPI (Python)
- **Storage**: Supabase (for file storage)
- **Frontend**: Jinja2 Templates + HTML/CSS
- **Async Streaming**: httpx + StreamingResponse
- **Deployment**: Docker + Render
- **Styles**: Pure CSS (Bootstrap-inspired)

---

## 🚀 Features

- 🎞️ Upload videos with custom titles
- 📺 Stream videos directly using range-based streaming
- 🗑️ Delete videos
- 📁 Supabase-backed object storage
- 🌐 Responsive interface with routing for `/`, `/watch/<video>`, `/upload`
- 🔐 Secure environment variable handling for Supabase credentials

---

## 📸 Screenshots

Coming soon...

---

## 🛠️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/amanmac9832/TaskMate---Keeps_you_on_track.git
cd TaskMate---Keeps_you_on_track
```

### 2. Create and activate a virtual environment

# On Windows

python -m venv .venv
.venv\Scripts\activate

# On macOS/Linux

python3 -m venv .venv
source .venv/bin/activate
