# Create repo on GitHub with README
git clone https://github.com/yourname/hello-world.git
cd hello-world
git checkout -b readme-edits
echo "Hello, GitHub" >> README.md
git add README.md
git commit -m "Add greeting"
git push -u origin readme-edits
