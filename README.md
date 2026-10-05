# \## Setup 

# Prerequisites: Python 3.10+, Git. 

# &#x20; 

# &#x20;   git clone https://github.com/nhvhuy2518-lab/lab01--nhvhuy-2518-.git 

# &#x20;   cd lab01-starter 

# &#x20;   python -m venv .venv 

# &#x20;   source .venv/bin/activate            # Windows: .venv\\Scripts\\Activate.ps1 

# &#x20;   pip install -r requirements.txt 

# &#x20;   pip install -e . 

# &#x20; 

# \## Run 

# &#x20;   python -m assistant "where is the library?" 

# &#x20;   # -> Library: room B.201, open Mon-Sat 07:00-20:00. 

# &#x20; 

# \## Test 

# &#x20;   pytest -q                              # -> 4 passed 

# &#x20; 

# \## Troubleshooting - "No module named assistant" -> you forgot `pip install -e .` or the venv is not active. - PowerShell blocks Activate.ps1 -> Set-ExecutionPolicy -Scope CurrentUser RemoteSigned

