# 620-mod6-web-scraping

See [BeautifulSoup Quickstart Guide](https://www.crummy.com/software/BeautifulSoup/bs4/doc/#quick-start)

Choose a BeautifulSoup parser:

- 'html.parser' (default, you get this with BeautifulSoup)
- 'html5lib' (install separately if desired)

## Getting Started

Fork (copy into your GitHub account) and clone down (to your machine) this repo to get started with web scraping.

## Requirements

    beautifulsoup4          # parsing webpages (HTML documents)
    html5lib                # parsing webpages (HTML documents)  - especially if poorly formatted
    ipykernel               # for Jupyter notebooks
    jupyterlab              # for Jupyter notebooks
    matplotlib              # customizing visualizations
    requests                # make HTTP requests (a very popular Python package)
    spacy                   # for NLP 
    spacytextblob           # for NLP - combines spaCy and TextBlob (simpler interface)

# datafun-07-ml
Intoduction to Predictive ML Project
Branton Dawson

## Dataset

Intro to machine learning (ML). At a high-level, there are three general categories of ML: supervised, unsupervised, and reinforcement learning. We'll employ a type of supervised learning, simple linear regression, to train a model and use the resulting model (a "best-fit" straight line) to make predictions.

## 1. Virtual Environment Management (Windows PowerShell)

1. **Create a virtual environment**
   ```powershell
   py -m venv .venv
   ```

2. **Activate the virtual environment**
   ```powershell
   .\.venv\Scripts\activate
   ```

3. **Upgrade pip, setuptools, and wheel**
   ```powershell
   py -m pip install --upgrade pip setuptools wheel
   ```

4. **Install required packages**
   ```powershell
   py -m pip install --upgrade -r requirements.txt
   ```

---

## 2. Running Python Scripts

```
- Activate your `.venv` and ensure all required packages are installed.
- Verify all external packages in your scripts are listed in `requirements.txt`.
```
---

## 3. Repeatable Workflow Checklist

When resuming work on your project, follow these steps:

1. [Pull latest changes](https://github.com/denisecase/pro-analytics-01/tree/main/03-repeatable-workflow)
2. Activate virtual environment
3. Install dependencies
4. Run Python scripts
5. Modify and test code
6. Add, commit, and push changes to Git

---

## 4. Git Add-Commit-Push CheatSheet

```powershell
git clone https://github.com/youraccount/yourrepo
git add .
git commit -m "custom message"
git push -u origin main
git pull origin main
git push
```

