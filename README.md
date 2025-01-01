# Information Retrieval System from Multiple PDF with PaLM2

# How to run?
### Steps:
Clone the repository

```bash
Project repo: https://github.com/
```
### STEP 01: Create a conda environment after opening the repo

``` bash
conda create -n llmapp python=3.8 -y
```

```bash
conda activate llmapp
```

### STEP 02: Install the requirements
```bash
pip install -r requirements.txt
```
# Create a .env file in the root directory and add your GOOGLE_API_KEY as follows:
```bash
GOOGLE_API_KEY= "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

# Finally run the following command
```bash
streamlit run app.py
```
Now,
```bash
open up : http://localhost:8501
```
### Techstack Used:

- Python
- LangChain
- Streamlit 
- PaLM2
- FAISS
