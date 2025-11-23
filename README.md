# best
better
# 1. make a temporary folder and copy the uploaded file as the README
mkdir "ld o,hl"
cd "ld o,hl"
cp /mnt/data/github_bio.txt README.md

# 2. initialize git, commit the README
git init
git add README.md
git commit -m "Add GitHub bio (from uploaded file)"

# 3. create the repo on GitHub and push (public repo — change to --private if you want)
gh repo create "ld o,hl" --public --source=. --remote=origin --push
