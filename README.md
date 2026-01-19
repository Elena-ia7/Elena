# Elena Nina 💻

Hi! I’m Elena, a beginner but passionate developer and AI enthusiast.  
I love creating **useful tools** and experimenting with **Python and AI**.  

---

## 🚀 Featured Project: PortfolioBot 🤖

**PortfolioBot** is a local AI-powered PC assistant built in Python.  
It interacts directly with the user’s computer to retrieve system information
and intelligently search for files and folders—even if you make typos!  

### 🔹 Features
- Intelligent folder search (supports typos and partial names)
- Accent-insensitive search (e.g., *ecole* → *école*)
- Disk memory usage info
- Suggests similar folders if an exact match is not found
- Natural language commands in French
- Runs locally, no internet required

### 🔹 How it works
- Python standard libraries
- File system exploration with `os.walk`
- Fuzzy string matching (`difflib`) + text normalization
- Command-line interface interaction

### 🔹 Example commands
```text
mémoire
dossier école
dossier ecol
chercher visa
exit

