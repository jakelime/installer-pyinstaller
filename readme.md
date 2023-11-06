# OfflineInstaller-Pyinstaller

## Instructions

1. Create requirements using `venv`

   ```powershell
   python -m venv venv
   .\venv\Scripts\activate
   pip install pyinstaller
   pip freeze > requirements.txt
   ```
   
1. Download as offline packages
 
   `pip download -r requirements.txt`

1. On the offline system, use `pip install --no-index --find-links . -r requirements.txt`

   ```powershell
   git clone https://github.com/jakelime/offlineinstaller-pyinstaller.git
   cd offlineinstaller-pyinstaller
   pip install --no-index --find-links . -r requirements.txt
   ```
