


## Steps to edit
- Clone locally or pull changes
- Edit files
- Preview locally
- Commit changes and push
- Check it has deployed on github

  or

Edit directly on github


### 1. Clone locally or pull changes

You can clone the repo
`git clone <repo-url>`

If you already have a copy of the repo locally make sure you pull the latest version
`git pull origin main`

### 2. Edit files
- about page: Edit `_pages/about.md`.

- blog posts: Make a new `.md` file in `_posts/` by copying an existing one.

- publications: Edit `_bibliography/papers.bib`

- cv: Edit `_data/cv.yml`

- configuration settings: Edit `_config.yml`


### 3. Preview files locally

You will need to install ruby: https://www.ruby-lang.org/en/documentation/installation/

Then install jekyll
```
gem install jekyll bundler
```

Setup this template by moving to the root folder of the repo and running
```
bundle install
pip install jupyter
```

build the html and serve it locally
```
bundle exec jekyll serve --lsi
```

You can preview it at
http://127.0.0.1:4000/test_webpage/


### 4. Commit changes and push

### 5. Check it is deployed on gh-pages
