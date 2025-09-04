## ⚡ Installation & Setup

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd <project-name>
```

### 2. Create and activate virtual environment
```bash
# Linux / macOS
python3 -m venv venv
source venv/bin/activate

# Windows
python -m venv venv
venv\Scripts\activate

```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Apply migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Run the development server
```bash
python manage.py runserver
```

Open 👉 http://127.0.0.1:8000/

---
