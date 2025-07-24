# 620-mod6 Web Scraping and NLP

## web scraping (fetching and extracting information) and processing the content from a web page

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

## Export notebook to HTML

   1. Use JupyterLab (or Jupyter Notebook) to export your .ipynb files as HTML. Try either:
      Using the Jupyter menu: File -> Save and Export As... -> HTML
   2. !jupyter nbconvert --to html name_of_notebook.ipynb
   3. import os
      os.system('jupyter nbconvert --to html yourNotebook.ipynb')

## Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

    (Question 1) Article html stored in separate file that is committed and pushed:
    (Question 2) Article text is correct:
    (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed:
    (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed:
    (Question 5) Correct scores for first sentence printed:
    (Question 6) Histogram shown with appropriate labelling:
    (Question 7) Histogram shown with appropriate labelling:
    (Question 8) Thoughtful answer provided:
