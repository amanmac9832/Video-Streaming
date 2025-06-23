# Video-Streaming

Video-Streaming is a simple, elegant video streaming and upload platform built with **FastAPI** and **Supabase Storage**. Users can upload, view, stream, and delete videos through a clean UI. Ideal for lightweight content management and learning cloud-based storage integration.

---

## 🔧 Tech Stack

- **Backend**: FastAPI (Python)
- **Storage**: Supabase (for file storage)
- **Frontend**: Jinja2 Templates + HTML/CSS
- **Async Streaming**: httpx + StreamingResponse

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

On Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

On macOS/Linux

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Set up environment variables

Create a .env file in the root directory:

```bash
SUPABASE_URL=https://your-project-id.supabase.co
SUPABASE_KEY=your-anon-key
SUPABASE_BUCKET=your-bucket-name
```

### 5. Run the server locally

```bash
uvicorn main:app --reload
```

Visit http://localhost:8000
