Google Collab URL: https://shorturl.at/oAJ7b
https://colab.research.google.com/drive/1f0ssCFr-KcNPq0OoDlEKiqtOI_kOkGoM?usp=sharing
https://colab.research.google.com/drive/1f0ssCFr-KcNPq0OoDlEKiqtOI_kOkGoM#scrollTo=KfS8ceBXRjcY
---------Git Config-----------
git config user.name "<user>"
git config user.email "<user@mail.com>"
git config credential.username "<user>"
-----------------------------------------
$ git init
$ git add .
$ git commit -m "First commit"

$ git remote add origin <remote repository URL>
# Sets the new remote
$ git remote -v
# Verifies the new remote URL

$ git push origin main
Otherwise you will have to name local branch first by
$ git branch -m <new_name>
and then push it to add a new branch called <new_name>
$ git push origin -u <new_name>
----------------------------------------
-----------------------
rag and agentic solution

cd existing_repo

git remote add origin https://github.com/rkj13780/rag-and-agentic-solution.git

git branch -M main

git push -uf origin main
