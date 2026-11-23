
## Installation

### 1. Install Python (Skip if already installed)

Open PowerShell or Terminal:

```powershell
winget install -e --id Python.Python.3.14
```

Close and reopen the terminal after installation.

### 2. Download the Project

**Option A — Download ZIP**

1. Open this repository.
2. Click **Code → Download ZIP**.
3. Extract the ZIP file.
4. Open the extracted folder in Terminal.

**Option B — Git Clone**

```powershell
git clone https://github.com/dulcodingz/foto-kita-blur.git
cd foto-kita-blur
```

### 3. Install Dependencies

Run inside the project folder:

```powershell
py -3.14 -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

### 4. Run the Application

```powershell
.\.venv\Scripts\python.exe blur.py
```

## How to Use

1. Make sure your webcam is connected.
2. Run the application.
3. Show a peace sign (✌️) in front of the camera.
4. The camera view will automatically blur.
5. Press **Q** or **ESC** to exit.
