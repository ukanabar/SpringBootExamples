…or create a new repository on the command line

echo "# SpringBootExamples" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/ukanabar/SpringBootExamples.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/ukanabar/SpringBootExamples.git
git push -u origin master