# Practics
Этот репозиторий содержит практики из курса по изучению Python.

Комнады чтобы отправить изменения с ПК на гит:

  !apt-get install -qq git
  
  from getpass import getpass
  import os os.environ['GITHUB_USERNAME'] = getpass('GitHub username:') os.environ['GITHUB_TOKEN'] = getpass('GitHub token:')

  !git clone https://github.com/<YOUR_GITHUB_USERNAME>/<REPO_NAME>.git

  git add . git commit -m "Your commit message" git push
